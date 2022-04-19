pipeline {
    agent any
    tools {
        maven 'maven-3.6.3' 
    }
    stages {
        stage('Example') {
            steps {
                sh 'git 'https://github.com/ruchi672/projectRepository.git'
            }
        }
	
	stage('Maven-Clean') {
            steps {
                sh 'mvn clean'
            }
        }
    }
}
