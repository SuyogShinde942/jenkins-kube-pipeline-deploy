
pipeline {
agent any
  stages {
    stage('abc'){
      steps {
        sh "kubectl apply -f deploy.yml --kubeconfig /admin.conf" 
      }
    }
  }
}
