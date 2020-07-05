node{
   stage('SCM Checkout'){
   git 'https://github.com/Abdulmuqtedir/jenkinsdemo.git'
   }
   
   stage('Clean'){
   sh 'mvn clean'
   
   }
   stage('Install'){
   sh 'mvn package'
   
   }
}
