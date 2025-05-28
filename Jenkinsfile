pipeline {
  agent any

  stages {
    stage('Pull Code') {
      steps {
        echo "Cloning repo and listing files"
        sh 'ls -al'
      }
    }
    stage('Build') {
      steps {
        echo "Build step simulated..."
      }
    }
    stage('Deploy') {
      steps {
        echo "Deploying to EC2 (simulated for now)"
      }
    }
  }
}
