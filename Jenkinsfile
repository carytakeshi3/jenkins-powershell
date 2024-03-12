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
                sh '.\script.ps1'
            }
        }
    }
}
