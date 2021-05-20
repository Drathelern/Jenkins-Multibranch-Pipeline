pipeline {
	agent any
		stages {
			stage('First') {
			    steps {
				 sh '''#!/bin/bash
					 echo "hello world" 
				 '''
			    }
			}

			stage('Second') {
				steps {
					 sh '''#!/bin/bash
					 echo "hello world" 
					 '''
				}
			} 

			stage('Thirds') {
				steps {
					sh '''#!/bin/bash
					 echo "hello world" 
					'''
				}
			}
		}
}
