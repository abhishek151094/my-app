pipeline {
  agent {
  label 'master'   
    
  } 
    stages {
        stage('---clean---') {
            steps {
                sh "mvn clean"
            }
        }
        
        stage('--package--') {
            steps {
                sh "mvn package"
            
            }
        }
    }
}
