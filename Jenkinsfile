pipeline {
  agent any
    stages {
      stage('Build') {
        steps {
          awsCodeBuild projectName: 'run-through-2',
                       credentialsId: 'run-through-us-east-2',
                       credentialsType: 'jenkins',
                       region: 'us-east-2',
                       sourceControlType: 'project'

        }
      }
    }
}
