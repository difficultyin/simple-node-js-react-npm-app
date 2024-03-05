pipeline {
    agent any
    tools {nodejs "/Users/mac/.nvm/versions/node/v18.17.1"}
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}