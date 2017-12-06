pipeline {
	agent any

	stages {
		stage('test') {
			steps {
				bat 'mvn test'
			}
		}
		stage('build') {
			steps {
				bat 'mvn build'
			}
		}
		stage('deploy') {
			steps {
				bat 'mvn tomcat7:deploy'
			}
		}
	}
}