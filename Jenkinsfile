pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        echo 'Hello from jenkins1 branch updated 3rd time'
      }
    }
    stage('Stage 1') {
      steps {
        echo 'Hello from stage 1'
      }
    }
    stage('Bye') {
      steps {
        echo 'Bye from jenkins1 branch updated 3rd time'
      }
    }
  }
  post {
    complete {
      echo "Build is successful"
    }
}
