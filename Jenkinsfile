pipeline{
    agent any 
    environment {
        CI = 'true'
    }
    stages {
        stage('Build') {
            steps {
                sh 'cat ./createpassword.py' // no output
        }
    }
        stage('test') { //  for test
            steps {
                sh 'echo done' 
        }
    }
  } 
}