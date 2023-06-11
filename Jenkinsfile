#!/usr/bin/env groovy
pipeline {
  agent any
    stages {
      stage('printing message') {
        steps {
          echo 'Hello World!'
        }
      }
      stage('storing value') {
        steps {
          script{
            def userEmail = "contact@josdem.io"
          }
        }
      }
      stage('reading value') {
        steps {
          script {
            print $userEmail
          }
        }
      }
   }
}
