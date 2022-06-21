pipeline {
    agent any
    
    environment {
       DISABLE_AUTH = 'true'
       JAVA_HOME = 'c:\Program Files\Java\jdk-11.0.15'
    }

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
