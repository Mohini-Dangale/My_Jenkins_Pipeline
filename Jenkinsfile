node {

 stage 'checkout'
 git url: 'https://github.com/Mohini-Dangale/My_Jenkins_Pipeline.git'
  
  def mvnHome = tool 'M3'

   // Mark the code build 'stage'....
   stage 'Build'
 
   // Run the maven build
    bat "${mvnHome}/bin/mvn clean test sonar:sonar"
   
   }
