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
		stage('Construir imagen'){
			steps{
				sh 'sudo docker build --tag=php54local .'
				sh 'sidp docker images|grep php54local'
			}
		}
	}
}
