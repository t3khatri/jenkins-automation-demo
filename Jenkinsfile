pipeline {
    agent {
    }
    stages {
        stage('Build') {
            steps {
                echo 'Build'
                sh 'mvn clean'
            }
        }
        stage('Test') { 
            steps {
                echo 'Build'
                sh 'mvn test' 
            }
        }
        stage('Deploy') { 
            steps {
                echo 'Build'
                sh 'mvn test' 
            }
        }      
        stage('Regresssion') { 
            steps {
                echo 'Build'
                sh 'mvn test' 
            }
        }            
      
        stage('Notification') { 
            steps {
                echo 'Build'
                sh 'mvn test' 
            }
        }                  
    }
}
