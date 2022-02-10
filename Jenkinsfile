

// Using git within checkout
pipeline {
    agent any
    stages {
        stage('Clean workspace') {
            steps {
                cleanWs()
            }
        }
	stage('list dir') {
	    steps {
		sh 'ls'
	    }
	}
    }
}

