pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'building....'
                bat "gradle build --refresh-dependencies"
            }
        }
        stage('Test') {
            steps {
                echo 'test'
                bat "set"
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
