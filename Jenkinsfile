pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh 'echo "Hello build number $BUILD_NUMBER of demo $DEMO"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}