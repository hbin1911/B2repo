pipeline{
  agent any

  stages{
    stage('Deploying site'){
      steps{
        publishHTML([allowMissing: false, alwaysLinkToLastBuild: false, keepAll: false, reportDir: '', reportFiles: 'index.html', reportName: 'HTML Report', reportTitles: '', useWrapperFileDirectly: true])
}
    }
  }
}
