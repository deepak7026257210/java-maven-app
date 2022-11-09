pipeline {
	agent any
	stages {
		stage(clone) {
                     steps {
                            git 'https://github.com/deepak7026257210/java-maven-app.git'
                              }
                             }
		stage('Build') {
			steps {
				sh 'mvn clean install'
			}
		   }
		
	          }
                 }
