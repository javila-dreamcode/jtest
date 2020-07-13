pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                sh 'npm init'
            }
        }

        stage('Unit Test') {
			steps {
				sh 'npm test '
			}                  
        }

    }
}