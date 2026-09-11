pipeline {
    agent any

    stages {

        stage('Checkout Validation') {
            steps {
                echo 'Repository cloned successfully'
                sh 'ls -la'
            }
        }

        stage('Build') {
            steps {
                echo 'Build successful'
            }
        }

        stage('Deploy') {
            steps {
                sh '''
                sudo cp index.html /var/www/html/index.html
                '''
            }
        }
    }
}
``
