pipeline{

agent any

stages{
	stage ('SCM'){
         		steps{
               		echo "git pull my code"
              		  }
                 }
         
	stage ('Deploy'){
                steps{
                      echo "deploying my code"
                     }
                    }
	stage ('Test'){
              steps{
                     echo "test my final webapp"
                   }
                  }
      }
 
}


