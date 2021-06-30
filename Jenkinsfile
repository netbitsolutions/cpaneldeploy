pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
				sh 'ssh -i /var/jenkins_home/.ssh/id_rsa  appcred@134.209.206.208 source /home/appcred/virtualenv/deploy/3.7/bin/activate'
                sh 'pip freeze'
            }
        }
    }
}