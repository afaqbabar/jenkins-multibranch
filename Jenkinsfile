pipeline {
    agent any
	triggers {
        githubPush()
    }

    stages {
        stage('Source') {
            steps {
                sh 'ls -la'
            } 
        
        }
        stage('Build') {
            steps {
                sh 'echo Hi from Build Stage'
            }
        }
        
        
    }
}