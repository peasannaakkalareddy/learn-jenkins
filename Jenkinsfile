pipeline {

  agent {
    node {
      label 'workstation'
    }
  }

  environment {
    SAMPLE_URL="example.com"
  }

  stages {

    stage( one ) {
      steps {
        sh 'echo Hello World'
        sh 'echo Hello Universe'
        sh 'echo ${SAMPLE_URL}'
      }
    }
  }
  post {
    always {
      sh 'echo cleanup steps'
    }
  }

}



