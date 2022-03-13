pipeline{
  agent any
  stages {
    stage('checkout'){
      Steps{
      git branch: 'main', url: 'https://github.com/Sandeepbori/devops-training.git'
    }
    }
    stage('Post Tasks'){
      Step{
      sh "echo Emailing"
      }
    }
  }
}
   
