pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    if (env.BRANCH_NAME == 'main') {
                        echo 'Running main'
                    }
                }
            }
        }
        stage('Test') {
            steps {
                script {
                    if (env.BRANCH_NAME == 'develop') {
                        echo 'Running develop'
                    }
                }
            }
        }
    }
}
