// Jenkinsfile
// ----------------------------------------------------------------------
// This is as simple as it gets with declarative pipeline
// ----------------------------------------------------------------------
pipeline {
  agent any parameters {
    choice(
      name: 'Env',
      choices: ['DEV', 'QA', 'UAT', 'PROD'],
      description: 'Passing the Environment'
    )
  }
   stages {
      stage('Say Hello') {
         steps {
            echo 'Hello World!'
         }
      }
   }
}