pipeline {
  agent any
  stages {
    stage('Init'){
      steps {
        echo 'Testing Process starts'
      }
      steps {
        echo 'Api Testing Process'
      }
      steps {
        echo 'Functional Testing Process '
      }
      steps {
        echo 'Performance Testing Process'
      }
      step {
        echo 'Testing Process Ends'
      }
    }

    stage('Build'){
      steps {
        echo 'Building process Starts...'
        }
      steps {
        echo 'Building process Ends'
      }
    }

    stage('Deploy'){
      steps {
        echo 'code Deployed'
      }
    }

  }

}
