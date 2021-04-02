Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker { image 'php' } }
    stages {
        stage('build') {
            steps {
                sh 'php --version'
                Copy-Item -Path "*" -Destination "C:\xampp\htdocs\WIS" -Recurse
            }
        }
    }
}