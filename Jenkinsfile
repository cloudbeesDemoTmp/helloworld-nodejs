pipeline {
  agent none
  stages {
    stage('Say Hello') {
      agent { label 'nodejs-app' }
      steps {
        echo 'We miss you Venus my pupper'
        echo 'We love you Venus'
        echo 'Hello World!'   
        sh 'java -version'
      }
    }
  }
}
