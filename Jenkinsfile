pipeline {
   agent any
	stages {
      stage('Git Checkout') {
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
