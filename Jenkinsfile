pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                sh 'git clone https://github.com/ruchi672/projectRepository.git'
            }
        }
	
	stage('Maven-Clean') {
            steps {
                sh 'mvn clean install'
            }
        }
    }
}
