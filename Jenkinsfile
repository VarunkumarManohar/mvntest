pipeline{
  
 agent any 
  parameters{
    
   string(name:'product_version', description:'version of the product')
   booleanParam(name:'is_external', description:'product is external')
  
  }
  stages{
    stage('say hello')
    {
      steps{
      
        sh 'echo "Hello" ' 
        
      }
      
    }
    
    
  }
 
}
