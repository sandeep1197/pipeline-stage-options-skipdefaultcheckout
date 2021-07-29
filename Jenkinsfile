pipeline {
    agent none
    stages {
        stage('Build') {
			agent any
		when {
			buildTag()
		}

            steps {                
                echo 'Building master branch'
            }
	}
		
        }
    }
