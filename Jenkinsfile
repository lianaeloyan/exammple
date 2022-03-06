
pipeline {
    agent { docker { image 'python:3.10.1-alpine' } }
    stages {
        stage('build') {
            steps {
             echo "Running ${env.BUILD_ID}"
                echo "MYVARNAME_USR MYVARNAME_PSW"
                parameters{
                        string(name: "Greating": HellO defaultValue:  "Hello", description: "How ")
}
                parameters.Greating ${defaultValue} World

        sh 'python --version'
            }
        }
    }
}
~   }
