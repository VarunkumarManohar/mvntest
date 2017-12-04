node{

  stage 'checkout'
  
  checkout scm
  
  def mvnhome= tool 'M2'
  
  stage 'build'
  sh '$mvnHome/bin/mvn clean install'


}
