pipeline {
	agent any
	stages {
		stage('Clone Repository') {
			steps {
				git branch: 'main', credentialsId: 'web-demo-github', url: 'https://github.com/Ms-Shoshany/web-demo.git'
			}
		}
		stage('Build') {
			steps {
				sh 'echo "building"'
			}
		}
		stage('test') {
			steps {
				sh 'echo "testing"'
			}
		}
		stage('Deploy') {
			steps {
				sh 'echo "deploying"'
			}
	}
}
