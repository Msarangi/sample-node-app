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
                sh'export http_proxy=proxy.intra.bt.com:8080' 
                sh'export https_proxy=proxy.intra.bt.com:8080'
                sh'npm install'
            }
        }
    }
}    
