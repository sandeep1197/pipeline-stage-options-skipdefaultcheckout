pipeline {
    agent none
    stages {
        stage('Build') {
			agent any
		when {
			branch 'master'
		}

            steps {                
                echo 'Building master branch'
            }
	}
		stage ('dev") {
		       
		when {
			branch 'dev'
		}
		       steps {
			       echo "Building dev branch"
		       }
		       }
        }
    }
