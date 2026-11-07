pipeline {
    agent { label 'linux && build' }

    stages {
        stage('Remote Check') {
            steps {
                echo 'Job is running on a remote agent'
                sh 'uname -m'
                sh 'hostname'
                sh 'sleep 30'
                sh 'whoami'
            }
        }
    }
}