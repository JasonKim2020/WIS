Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker { image 'php' } }
    stages {
        stage('build') {
            steps {
                sh 'php --version'
                sh 'copy * C:\xampp\htdocs\WIS'
            }
        }
    }
}