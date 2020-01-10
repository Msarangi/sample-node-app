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
                sh'npm config set http-proxy http://proxy.intra.bt.com:8080'
                sh'npm config set https-proxy https://proxy.intra.bt.com:8080'
                sh'npm install'
            }
        }
    }
}    
