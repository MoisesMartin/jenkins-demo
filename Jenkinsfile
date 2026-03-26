pipeline {
    agent any

    stages {
        stage('Checkout Info') {
            steps {
                echo 'Code was pulled from GitHub'
            }
        }

        stage('Run Demo') {
            steps {
                sh 'cat app.js'
                echo 'Pipeline executed successfully'
            }
        }
    }
}
