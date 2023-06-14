pipeline {

  agent {
    node {
      lable 'workstation'
    }
  }

  stages {

    stage( one ) {
      steps {
        sh 'echo Hello World'
      }
    }
  }
  post {
    always {
      sh 'echo cleanup steps'
    }
  }

}



