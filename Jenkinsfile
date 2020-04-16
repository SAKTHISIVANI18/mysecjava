pipeline {

agent any
   
   stages {
   
   stage('compile'){
    steps{
     sh 'cd /var/lib/jenkins/workspace/npipe'
       sh 'javac sv.java'
       sh 'java aaa'
    }
   }
      stage('deploy'){
      steps{
         sh 'cd /var/lib/jenkins/workspace/npipe'
         sh ' cp /var/lib/jenkins/workspace/npipe /home/dineshreddy99077/noida/apache-tomcat-7.0.103/webapps/'
      }
      }
   }
}
