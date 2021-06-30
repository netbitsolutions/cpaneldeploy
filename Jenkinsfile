pipeline {
    agent any
    stages {
        stage('build') {
            steps {
				sh 'ssh credapp@134.209.206.208 source /home/appcred/virtualenv/deploy/3.7/bin/activate && cd /home/appcred/deploy'
                sh 'pip freeze'
            }
        }
    }
}