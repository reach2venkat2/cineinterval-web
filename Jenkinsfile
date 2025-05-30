pipeline {
  agent any

  stages {
    stage('Clone Repo') {
      steps {
        echo "📥 Cloning GitHub repo"
        sh 'git clone https://github.com/reach2venkat2/cineinterval-web.git workspace'
      }
    }

    stage('Deploy to EC2') {
      steps {
        echo "🚀 Deploying to EC2 (NGINX)"
        sh 'sudo cp workspace/index.html /usr/share/nginx/html/index.html'
      }
    }
  }
}
