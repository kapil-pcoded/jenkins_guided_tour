pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World1233"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}