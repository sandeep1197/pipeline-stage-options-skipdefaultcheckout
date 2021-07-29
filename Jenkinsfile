pipeline {
    agent none
    stages {
        stage('Build') {
			agent any
		when {
			tag = "t1" 
		}

            steps {                
                echo 'Building master branch'
            }
	}
		
        }
    }
