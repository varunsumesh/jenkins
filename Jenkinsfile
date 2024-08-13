pipeline {
    agent {label 'one' }  

    stages {
        stage('Build') {
            steps {
                echo 'Building for test..'
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
