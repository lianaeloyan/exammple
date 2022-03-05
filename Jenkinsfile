pipeline {
    agent { docker { image 'python:3.10.1-alpine' } }
    stages {
        stage('build') {
            steps {
             echo "Running ${env.BUILD_ID}"
		echo "MYVARNAME_USR MYVARNAME_PSW"
   	sh 'python --version'
            }
        }
    }
}
