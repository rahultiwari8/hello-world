pipeline {
  agent none
  stages {
    stage('build') {
      steps {
        sh 'mvn clean install'
        mail(subject: 'Test-hello -world', body: 'none', from: 'rahtiwari@gmail.com', to: 'rahtiwari@gmail.com', replyTo: 'rahtiwari@gmail.com')
      }
    }

  }
}