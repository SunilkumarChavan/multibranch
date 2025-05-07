i
#Edited on Feature branch
node('master') 
{
  stage('ContinuousDownload_master') 
  {
    git 'https://github.com/selenium-saikrishna/maven.git'
  } 
  stage('ContinuousBuild_master') 
  {
    sh 'mvn package'
  } 
  }
