pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                script{
                sh './gradlew build'
                }
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                script {
                sh './gradlew test'
                }
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
