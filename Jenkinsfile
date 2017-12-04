node{

  stage 'checkout'
  
  checkout scm
  
  def mvnhome= tool 'M2'
  
  stage 'build'
  sh 'mvn clean install'


}
