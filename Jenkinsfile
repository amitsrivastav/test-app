pipeline {
    agent { docker 'hello-world' }
    stages {
        stage('build') {
            steps {
               sh 'mvn --version'
            }
        }
    }
}