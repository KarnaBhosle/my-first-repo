pipeline{
  agent any

  stages{
    stage('Checkout'){
      steps{
            git 'https://github.com/KarnaBhosle/my-first-repo'
    }
    }
    stage('Publish'){
      steps{
        publishHTML([
          allowmissing:true,
          alwaysLinktoLastBuild:false,
          KeepAll:false,
          reportDir:'.',
          reportFiles:'index.html',
          reportName:"MY HTML PAGE'
          ])
      }
    }
          
      

  }
