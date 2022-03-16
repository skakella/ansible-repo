pipeline {
  agent any
  stages {
    stage('Git-Checkout') {
      steps {
        git(url: 'https://github.com/skakella/ansible-repo.git', branch: 'master')
      }
    }

  }
  environment {
    build = 'anisble'
  }
}