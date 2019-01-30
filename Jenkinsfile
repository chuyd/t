pipeline {
  agent {
    node {
      label 'bare-metal'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'echo Build'
      }
    }
    stage('postbuild2') {
      steps {
        sh 'echo Postbuild3'
      }
    }
    stage('end') {
      steps {
        sh 'echo end'
      }
    }
  }
}
