pipeline {
    agent none
    stages {
        stage('Build') {
			agent any
		when {
		        tag = "t2"
		}

            steps {                
                echo 'Building master branch'
            }
	}
		
        }
    }
