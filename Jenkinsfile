pipeline {
  agent any
  stages {
    stage('tools') {
      steps {
        tool(name: 'Maven 3.3.9', type: 'maven')
        tool(type: 'jdk', name: 'jdk-1_8_0_40')
      }
    }
    stage('build') {
      steps {
        bat 'echo "Hello World"'
      }
    }
  }
}