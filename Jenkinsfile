pipeline {
    agent any
    stages {
        stage('version') {
            steps {
                sh '$PSVersionTable.PSVersion'
            }
        }
        stage('runscript') {
            steps { 
                sh 'powershell -File script.ps1'
            }
        }
    }
}
