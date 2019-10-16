pipeline {
    agent {
        label 'Sandbox-79'
        }

    stages {
		stage('Build') 
		{ 
         	steps {
			checkout scm
			echo 'Build is in progress'
                }	
        } 
        stage('Test') 
		{
            steps {
            	echo 'Testing...'
            	}
        }
    }
}
