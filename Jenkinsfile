pipeline {
    agent any

    stages {
        stage('Chekout') {
            steps {
                git branch: 'main', url: 'https://github.com/kvnyijia/task.git'
                echo 'Checkout Completed'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
