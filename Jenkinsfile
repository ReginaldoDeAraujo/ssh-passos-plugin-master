node { 	
   stage('Git') {
		git 'https://github.com/ReginaldoDeAraujo/connect-ssh'
	}
	stage('Build') {
		sh 'npm install'
	}
	stage('Test') {
		sh 'npm test'
	}    
}

