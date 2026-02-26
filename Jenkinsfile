pipeline {
  agent any
  
   stages {
    stage('clone') {
     steps {
       git url:"https://github.com/ashwaja/jenkins-simple-demo.git"
         branch: 'main'
     }
   }
   stage('Run Script') {
     steps {
       sh 'chmd +x script.sh'
       sh '/.script.sh
      }
   }
 }
}
