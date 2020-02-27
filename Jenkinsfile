pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('Compile') {
            steps {
                sh 'python script.py'
            }
	}
	stage('Testing Stage') {
            steps {
                sh 'python test'
            }
	}
	stage('Deployment Stage') {
            steps {
                sh 'python deploy'
            }
        }
	
      }
}
