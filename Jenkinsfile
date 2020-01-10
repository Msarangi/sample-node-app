pipeline{
    agent any
    tools {nodejs "Node_Build"}
    stages {
        stage('Build') {
            steps {
                echo'hi'
                sh'pwd'
                // Run the npm build
                //sh'export PATH=/usr/local/bin'
                //sh'node --version'
                sh'npm --version'
                //sh 'npm install'
            }
        }
    }
}    
