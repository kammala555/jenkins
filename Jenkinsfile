pipeline {
   agent any
   stages {
     stage('build') {
        step {
          echo "building is successful"
        }
     }
     stage('test') {
       step {
         echo "testings"
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
