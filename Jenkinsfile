pipeline{
    agent any
    stages {
        stage('Build') {
            steps {
                echo'hi'
                // Run the npm build
                //sh'export PATH=/usr/local/bin'
                //sh'node --version'
                //sh'npm --version'
                sh '/root/.nvm/versions/node/v13.6.0/bin/npm npm install'
            }
        }
    }
}    
