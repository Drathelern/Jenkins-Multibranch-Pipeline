pipeline {
	agent any
		stages {
			stage('One') {
			    steps {
				 sh '''#!/bin/bash
					 echo "hello world" 
				 '''
			    }
			}

			stage('Two') {
				steps {
					 sh '''#!/bin/bash
					 echo "hello world" 
					 '''
				}
			} 

			stage('Three') {
				steps {
					sh '''#!/bin/bash
					 echo "hello world" 
					'''
				}
			}
		}
}
