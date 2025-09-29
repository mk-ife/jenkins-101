pipeline {
  agent any
  options { timestamps() }
  stages {
    stage('Checkout')    { steps { checkout scm } }
    stage('Build Dummy') { steps { sh 'echo "Repo build OK"' } }
    stage('Success')     { steps { echo 'done' } }
  }
}
