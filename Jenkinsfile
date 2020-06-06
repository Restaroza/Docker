pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo '$BUILD_NUMBER of demo'
        sh 'echo "This is build $BUILD_NUMBER of demo $DEMO"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}