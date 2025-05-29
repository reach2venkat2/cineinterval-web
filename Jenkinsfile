pipeline {
  agent any

  stages {
    stage('Pull Code') {
      steps {
        echo "Pulling latest code"
        sh 'ls -al'
      }
    }

    stage('Deploy to EC2') {
      steps {
        echo "Deploying to nginx root"
        sh 'sudo cp index.html /usr/share/nginx/html/index.html'
      }
    }
  }
}
