pipeline {
	agent any
	stages{
		stage('Primera inicializacion'){
			steps{
				sh 'echo inicializando...'
			}
		}
		stage('Checando docker'){
			steps{
				sh 'sudo docker ps'
			}
		}
	}
}
