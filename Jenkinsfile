pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh 'echo "this is build $BUILD_NUMBER of job $DEMO"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}