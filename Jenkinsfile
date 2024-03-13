pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Test') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Hello World'
            }
        }
    }
    {post{
        always{
            emailext body: 'jhdsgvfjgsj', subject: 'any', to: 'charanpatgar19@gmail.com''
        }
    }
}
