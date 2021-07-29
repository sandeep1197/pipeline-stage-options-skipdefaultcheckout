pipeline {
    agent none
    stages {
        stage('Build') {
			agent any
		when {
		        tag "release-*"
		}

            steps {                
                echo 'Building master branch'
            }
	}
		
        }
    }
