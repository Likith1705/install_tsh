pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Installing Dependencies..'
            }
        }
        stage('Deploy') {
            steps {
		    sh "chmod +x ./tsh_init.sh"
                sh "./tsh_init.sh"
	    }
        }
    }
}
