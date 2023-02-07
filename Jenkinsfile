pipeline{

agent any

stages{
	stage ('SCM'){
         		steps{
               		echo "git pull my code"
                        git 'https://github.com/girisankardevops/simple-java-maven-app.git'
              		  }
                 }
         
	stage ('Build'){
                steps{
                      sh 'mvn clean package'
                     }
                    }
	stage ('Test'){
              steps{
                     echo "test my final webapp"
                   }
                  }
      }
 
}


