pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'docker build --tag people:dev'
      }
    }

  }
  environment {
    port = '80'
  }
}