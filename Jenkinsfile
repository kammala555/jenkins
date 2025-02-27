pipeline {
   agent any
   stages {
     stage('build') {
        step {
          echo "building"
        }
     }
     stage('test') {
       step {
         echo "testing"
      }
    }
    stage('deploy') {
      step {
        echo "deployings"
      }
    }
  }
   post {
     always {
        echo 'this will always run'
      }
      success {
        echo 'this is successed'
       }
       failure {
         echo 'this is failed'
        }
    }
}
