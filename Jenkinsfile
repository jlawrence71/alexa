pipeline {
    agent { docker 'node:6.3' }
    stages {
        stage('Build') {
            steps {
                sh 'npm --version'
            }
        }
		stage('Test') {
		            steps {
		                sh 'echo "Howdy !!"; exit 0'
		            }
		        }        
    }
}