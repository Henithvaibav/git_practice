pipeline{
agent any
stages{
stage('SCM_checkout'){
steps{
//define git
}
stage('maven build'){
steps{
sh 'mvn clean package'
}
}
  stage('Slack Notification'){
    steps{
      //configure slack notification
    }
}
}
}
