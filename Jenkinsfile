
pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                echo 'Python Compile'
            }
        }
        stage('Unit test'){
        	steps{
        		sh "python test.py"
        	}
        
        }
    }
}

