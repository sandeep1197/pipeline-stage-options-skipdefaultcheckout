pipeline {
    agent none
    stages {
        stage('Build') {
			agent any
		when {
		        tag "2.0"
		}

            steps {                
                echo 'Building master branch'
            }
	}
		
        }
    }
