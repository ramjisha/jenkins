pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello, World!  checking'
            }
        }

        stage('Create Directory') {
            steps {
                script {
                    def dirPath = 'new_directory'
                    sh "mkdir -p ~/${dirPath}"
                }
            }
        }
    }
}
