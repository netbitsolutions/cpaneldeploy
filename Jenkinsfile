pipeline {
    agent any
    stages {
        stage('build') {
            steps {
				sh 'source /home/appcred/virtualenv/deploy/3.7/bin/activate && cd /home/appcred/deploy'
                sh 'pip freeze'
            }
        }
    }
}