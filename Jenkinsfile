pipeline {
    agent { docker 'node:6.3' }
    stages {
        stage('build') {
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