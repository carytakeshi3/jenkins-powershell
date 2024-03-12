
pipeline {
    agent any
    stages {
        stage('version') {
            steps {
                sh 'pwsh --version'
            }
        }
        stage{'runscript'}{
            steps{ 
                sh 'pwsh script.ps1'
            }
        }
    }
}
