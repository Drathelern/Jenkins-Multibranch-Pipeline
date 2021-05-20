pipeline {
	agent any
		stages {
			stage('First') {
			    steps {
				 sh '''#!/bin/bash
					 echo "hello world" 
				 '''
			    }
			    steps {
				script {
					env.VARIABLE="value"
				}
			    }
			}

			stage('Second') {
				steps {
					 sh '''#!/bin/bash
					 echo "hello world" 
					 '''
				}
			} 

			stage('Third') {
				steps {
					sh '''#!/bin/bash
					 echo "hello world" 
					
				}
			}
			
			
		}
}
