pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                bat 'python welcome.py'
                bat 'python click.py'
            }
        }
    }
}
