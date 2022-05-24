pipeline {
    agent any
  tools{
  
    maven 'maven'
  
  }
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
      
       stage('build') {
            steps {
                sh 'maven package'
            }
        }
      
      
    }
}
