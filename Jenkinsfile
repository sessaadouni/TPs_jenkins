pipeline {
  agent any
  
  stages {
    stage('Setup') {
      steps {
        echo "Starting..."
      }
    }
      
    stage('Execute Script') {
      steps {
        script {
          sh 'python3 /var/jenkins_home/TPs/TP1/hello_world.py'
        }
      }
    }
  }
}