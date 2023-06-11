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
          System.setProperty("customer.email", "contact@josdem.io")
        }
      }
      stage('storing value') {
        steps {
          print System.properties["customer.email"]
        }
      }
   }
}
