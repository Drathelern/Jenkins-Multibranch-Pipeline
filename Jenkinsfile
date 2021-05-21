pipeline {
	agent any
		stages {
			stage('First') {			
				steps {
					sh '''#!/bin/bash
						echo "Step -One"
					'''
					script {
						env.EXECUTE = "True"
					}
				}
			}


			stage('Second') {
				steps {
					sh '''#!/bin/bash
						echo "Step -Two"
					'''
				}
			} 

			stage('Third'){
				steps {
					sh '''#!/bin/bash
						echo "Step -Three"
					'''
				}
			}
		}
}
