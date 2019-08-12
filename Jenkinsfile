node('master') 
  stage 'build'
  openshiftBuild(buildConfig: 'cotd', showBuildLogs: 'true')
  stage 'deploy'
  openshiftDeploy(deploymentConfig: 'cotd')
  
