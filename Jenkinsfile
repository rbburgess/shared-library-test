@Library('shared-library') _
pipeline {
  agent any
  stages {
    stage('Test') {
        steps{
            script {
                helloWorld("Bob")
                gitStatus()
                getVersion()
                setVersion("1.149.27")
                getVersion()
            }
        }
    }

  }

}