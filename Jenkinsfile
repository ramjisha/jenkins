pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello, Worl you checking !!!!!'
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
