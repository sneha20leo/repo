pipeline
 {
 agent any
 stages{
 stage('Build Application'){
 steps{
 
 bat 'mvn clean install'
 }}
 
 stage('Deploy Application to Mulesoft Cloudhub'){
 steps{
 bat 'mvn -e -X clean package deploy -DmuleDeploy'
 }
 
 }
 }
}
