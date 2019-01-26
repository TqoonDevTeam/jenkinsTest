pipeline{
  agent any
  stages{
    stage('Test'){
      steps {
        echo "Hello world"
        echo '======== env ========='
        echo sh(returnStdout: true, script: 'env')
        echo '======== /env ========='
      }
    }
  }
}
