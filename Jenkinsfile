pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                echo 'checking source code'
            }
        }

        stage('build') {
            steps {
                echo 'building source code'
            }
        }

        stage('test') {
            steps {
                echo 'testing source code'
            }
        }
    }

    post {
        success {
            echo 'pipeline successfully completed'
        }
    }
}