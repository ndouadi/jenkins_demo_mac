pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'brew install node'
                sh 'node app.js'
            }
        }
    }
}
