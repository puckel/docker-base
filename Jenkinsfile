pipeline {
  options {
    ansiColor colorMapName: 'XTerm'
  }
  stages {
    stage('Build') {
      steps {
        sh "docker build --rm -t puckel/docker-base:${GIT_SHA} ."
      }
    }
  }
}
