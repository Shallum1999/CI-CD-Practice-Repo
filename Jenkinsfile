
pipeline {
    agent any
    triggers {
        cron('9 * * * *')
    }
    stages {
        stage('Compile') {
            steps {
                echo 'Python Compile'
            }
        }
        stage('Unit test'){
        	steps{
        		sh "python3 test.py"
        	}
        
        }
    }
}

