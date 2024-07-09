pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
	         git branch:'main',credentialsId:'github-token', 
                        url:'https://github.com/dowon0113/test_jenkins2.git'
	        }
        }
    }
}
