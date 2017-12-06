pipeline {
	agent any

	stages {
		stage('test') {
			steps {
				bat 'mvn test'
			}
		}
		stage('display') {
			steps {
				bat 'mvn build'
			}
		}
	}
}