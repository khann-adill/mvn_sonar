  
pipeline {
   agent any
	stages {
      stage('Checkout') {
         steps {
            //git 'https://github.com/khann-adill/mvn_sonar.git'
		 checkout scm
		}
	}
    stage('test') {
      steps {
        sh 'echo hi..'
      }
    }
}
}
