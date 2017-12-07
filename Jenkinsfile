node{

  stage 'checkout'
  
  checkout scm
  
  def mvnhome= tool 'M2'
  echo mvnhome
  
  stage 'build'
  sh 'mvn clean install' 
  
  
  
  stage 'ask for input'
  input 'ready to go ?'


}
