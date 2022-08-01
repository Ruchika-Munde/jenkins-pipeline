node {
	stage 'Fetch code from GitHub'
		git branch: 'main', url: 'https://github.com/Ruchika-Munde/jenkins-pipeline.git'
	stage 'Install and start Apache'
		sh 'sudo apt-get install apache2 -y'
		sh 'sudo service apache2 start'
	stage 'Deploy code'
		sh 'sudo cp -R * /var/www/html/'
}

