node{

  stage 'checkout'
  
  checkout scm
  
  def mvnhome= tool 'M2'
  echo mvnhome
  
  stage 'build'
  sh '$mvnhome/bin/mvn clean install'


}
