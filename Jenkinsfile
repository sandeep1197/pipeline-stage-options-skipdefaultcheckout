pipeline {
    agent none
    stages {
        stage('Build') {
			agent any
		when {
			buildingTag()
		}

            steps {                
                echo 'Building master branch'
            }
	}
		
        }
    }
