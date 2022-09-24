pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'mvn clean install -Dversion.webxml=30'
      }
    }
  }
}
