
pipeline {
    agent any
    triggers {
        cron('H */4 * * 1-5')
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

