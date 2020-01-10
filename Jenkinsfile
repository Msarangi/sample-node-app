pipeline{
    agent any
    stages {
        stage('Build') {
            steps {
                echo'hi'
                sh'pwd'
                // Run the npm build
                //sh'export PATH=/usr/local/bin'
                //sh'node --version'
                sh'/var/lib/jenkins/workspace/nodejs npm --version'
                //sh 'npm install'
            }
        }
    }
}    
