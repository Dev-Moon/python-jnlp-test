pipeline {
    agent {
        label 'python-test'
    }

    stages {
        stage('Build') {
            steps {
                sh "python3 test.py"
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
