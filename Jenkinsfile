pipeline {
    agent any

    
    stages {
        stage('Maven Build') {
            steps {
                echo 'Maven Building..'
            }
        }
        stage('Unit Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Build Image') {
            steps {
                echo 'auto build docker images..'
            }
        }
        stage('Push Image') {
            steps {
                echo 'Push App images to private registry..'
            }
        }
        stage('Deploy Containers') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
