pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'mvn clean'
        sh 'mvn install -Dversion.webxml=25'
      }
    }
  }
}
