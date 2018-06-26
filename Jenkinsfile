
pipeline {
     agent { docker { image 'microsoft/azure-cli' } }
     
    stages {
        stage('confirm container') {
            steps {
                sh 'echo "*************************************************************"'
                sh 'ls -la'
            }
        }
    }
}