pipeline {
    agent { label 'master'}
    stages {
        stage('build') {
            steps {
                echo "This is buld step"
                sh 'echo using shell within Jenkinsfile'
                echo 'not using shell in the Jenkinsfile'
            }
        }
    }
}
