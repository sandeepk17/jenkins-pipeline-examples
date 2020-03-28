// Jenkinsfile
// ----------------------------------------------------------------------
// This is as simple as it gets with declarative pipeline
// ----------------------------------------------------------------------
  pipeline {
  agent any
  parameters {
    string(defaultValue: "defaultParam2", description: 'What is defaultParam2 ?', name: 'defaultParam2')
    choice(
        name: 'myParameter',
        choices: ['DEV', 'QA', 'UAT', 'PROD'],
        description: 'interesting stuff' )
  }
  stages {
    stage('Environment') {
      steps {
        echo " The environment is ${params.myParameter}"
      }
    }
  }
}