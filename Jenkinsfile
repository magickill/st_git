pipeline {
  agent {
    node {
      label 'work1'
    }

  }
  stages {
    stage('stage_one') {
      steps {
        echo 'add stage one for test'
        sleep 1
        sh 'echo "shell output in stage one"'
      }
    }

  }
  environment {
    SC_USER = 'zjk'
    SC_EMAIL = '79127437@qq.com'
  }
}