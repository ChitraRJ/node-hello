pipeline {
  agent any
  tools {nodejs "Nodejs"}
  stages {
      
    stage('Git') {
      steps {
        echo 'hi49f5'
        git 'https://github.com/johnpapa/node-hello.git'
      }
    }
     
    stage('Build') {
      steps {
        sh 'npm install'
        sh 'npm run'
      }
    } 
    
            

}
}
