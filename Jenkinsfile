pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                // This clears the workspace and gets the code
                cleanWs() 
                checkout scm
            }
        }
        stage('Debug & Run') {
            steps {
                // This will list all files so you can see where script.py is
                sh 'ls -R' 
                sh 'script.py'
            }
        }
    }
}
