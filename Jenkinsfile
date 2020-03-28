// Jenkinsfile
// ----------------------------------------------------------------------
// This is as simple as it gets with declarative pipeline
// ----------------------------------------------------------------------
  pipeline {
  agent any
  parameters {
    choice(
        name: 'myParameter',
        choices: "Option1\nOption2",
        description: 'interesting stuff' )
  }
}