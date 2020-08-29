pipeline{

 agent {label 'Java'}

 environment{

 PATH = "/usr/share/maven/bin:$PATH"

 }


 stages{


 stage("maven build")
 {

 steps{


 sh "hostname"

 sh "mvn clean package"

    }

 }

 }

 }
