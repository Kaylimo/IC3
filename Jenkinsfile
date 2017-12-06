pipeline {
	agent any

	stages {
		stage('read repository') {
			steps {
				bat 'git fetch'
			}
		}
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