pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                bat 'python welcome.py'
                bat 'python click.py'
            }
        }
    }
}
