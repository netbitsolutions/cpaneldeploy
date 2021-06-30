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
				sh(script: 'ssh -i /var/jenkins_home/.ssh/id_rsa  appcred@134.209.206.208 pip freeze', returnStdout: true)
			
            
            }
        }
    }
}