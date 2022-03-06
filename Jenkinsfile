pipeline {
    agent any
    parameters{
	string(name: "Greating": defaultValue:  "Hello", description: "First")
	string(name: "Sec": defaultValue:  "World", description: "Second ")	
}
    stages {
        stage('build') {
            steps {
            	 echo "Running ${params.Greeting}, ${params.Sec}"
            }
        }
    }
}
~   }
