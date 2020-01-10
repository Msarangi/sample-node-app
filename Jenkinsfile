pipeline{
    agent any
    tools {nodejs "Node-Build"}
    stages {
        stage('Build') {
            steps {
                sh'pwd'
                // Run the npm build
                sh'node --version'
                sh'npm --version'
                sh'npm install'
            }
        }
    }
}    
