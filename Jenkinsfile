pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/pillmayr/jenkins.dockertest', branch: 'master')
      }
    }
  }
}