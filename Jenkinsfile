pipeline {
  agent any
  tools {
    maven 'MAVEN3'
  }
  stages {
    stage ('checkout'){
	  steps {
	    git 'https://github.com/djgio02/spring-petclinic.git'
	  }
	}
	stage ('Build'){
	  steps{
	    sh 'mvn clean compile'
	  }
	}
  }
}