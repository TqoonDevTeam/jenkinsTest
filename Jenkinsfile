pipeline{
    agent any
    stages{
        stage('Test'){
            steps {
                echo '======== env ========='
                echo sh(returnStdout: true, script: 'env')
                echo '======== /env ========='
            }
        }
    }
}
