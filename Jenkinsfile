pipeline {
    agent any
  tools{
  
    maven 'maven-3.8.5'
  
  }
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
      
       stage('build') {
           
           when{
               
               expression{
                   
                BRANCH_NAME == 'master'   
                   
                   
               }
           }
            steps {
                sh 'mvn package'
            }
        }
      
      
    }
}
