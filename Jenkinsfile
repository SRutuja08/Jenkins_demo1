pipeline
{
agent any
stages
{
stage('scm checkout')
 {steps {git branch: 'main', url: 'https://github.com/SRutuja08/Jenkins_demo1.git'}}       //sh=execute shell

stage('print your message')
  {steps{sh 'echo hello'
         sh 'echo this is jenkins file'}}  //sh=execute shell
}
}
