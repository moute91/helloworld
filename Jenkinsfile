pipeline {
  agent any
  tools {
    maven 'M2_HOME'
  }
  stages {
    stage ('build') {
      steps{
      sh 'mvn clean'
      sh 'mvn install'
      sh 'mvn package'  
        sleep 4
      }
    }
    stage ('test') {
      steps{
      echo "hello test"
      sh 'mvn test'
        sleep 4
      }
    }
    stage ('dev') {
      steps{
      echo "how are dev team"
        sleep 4
      }
    }
    stage ('deploy') {
      steps{
      echo "what is deploying"
        sleep 4
      }
    }
  }
}
