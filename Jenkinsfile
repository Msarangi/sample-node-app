pipeline{
    agent any
    stages {
        stage('Build') {
            steps {
                // Run the npm build
                node --version
                npm --version
                sh 'npm install'
            }
        }
    }
}    
