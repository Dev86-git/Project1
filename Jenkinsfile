pipeline {
  agent { label 'slave5' }	
    stages {
        stage('example') {   
          when {
            branch 'dev'
          }
            steps {
               echo "testing"
            }
        }
      stage('testing') {   
          
        steps {
               echo "testing"
            }
        }
    }
}
