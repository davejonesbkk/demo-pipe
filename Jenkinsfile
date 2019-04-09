
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World, this is an automated build"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
