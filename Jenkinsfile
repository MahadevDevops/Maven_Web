pipeline {
  agent any
  stages {
    stage('Checkout SCM') {
      steps {
        git(url: 'https://github.com/MahadevDevops/Maven_Web.git', branch: 'master', poll: true)
      }
    }
    stage('Build') {
      steps {
        echo 'Im in build'
      }
    }
  }
}