node {
    
    stage('Git Clone') {
	  git branch: 'main', credentialsId: 'git234', url: 'https://github.com/Ranjithchary/kiran.git'
    }
    stage('Maven Clean') {
       
    }
    stage('Maven Validate') {
       bat 'mvn clean'
	}
	stage('Maven Compile') {
       bat 'mvn clean'
	}
	stage('Maven Test') {
        bat 'mvn clean'
	}
	stage('Maven Package') {
       bat 'mvn clean'
	}
	
}