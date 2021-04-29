
pipeline {
agent any
  stages {
    stage('abc'){
      steps {
        kubernetesDeploy(config: "deploy.yml" , kubeconfigId: "mykubeconfigfile")
      }
    }
  }
}
