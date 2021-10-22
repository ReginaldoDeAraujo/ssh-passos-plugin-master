node { 	
   stage('Git') {
		git 'https://github.com/ReginaldoDeAraujo/ssh-passos-plugin-master.git'
	}
	stage('Build') {
		sh 'npm install'
	}
	stage('Test') {
		sh 'npm test'
	}    
}

