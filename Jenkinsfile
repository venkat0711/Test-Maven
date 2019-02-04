pipeline {
  agent any
  stages {
    stage('Clone') {
      steps {
        echo 'Building..'
        sh 'git clone https://github.com/venkat0711/Test-Maven.git/'
      }
    }
    stage('Unit Test') {
      steps {
        echo 'Testing..'
      }
    }
    stage('Build') {
      steps {
        echo 'Deploying....'
      }
    }
    stage('Artifacts To Nexus') {
      steps {
        echo 'Move Artifacts to Nexus'
      }
    }
    stage('DEV Deployment') {
      steps {
        echo 'Deploy in Dev'
      }
    }
  }
}