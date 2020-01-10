pipeline{
    agent any
    stages {
        stage('Build') {
            steps {
                // Run the npm build
                export PATH=$PATH:/usr/local/bin
                sh 'npm install'
            }
        }
    }
}    
