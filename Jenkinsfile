pipeline {
  agent {
    node {
      label 'bare-metal'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'echo build'
      }
    }
    stage('postbuild2') {
      steps {
        sh 'echo postbuild'
      }
    }
    stage('end') {
      steps {
        sh 'echo end'
      }
    }
  }
}