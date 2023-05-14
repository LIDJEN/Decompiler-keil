pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    when {
                        branch 'main' 
                    }
                    echo 'Running main'
                }
            }
        }
        stage('Test') {
            steps {
                script {
                    when {
                        branch 'develop'
                    }
                    echo 'Running develop'
                }
            }
        }
    }
}
