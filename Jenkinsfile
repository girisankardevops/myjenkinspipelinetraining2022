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
	stage ('Deploy'){
              steps{
                     Sh 'java -jar target/*.jar'
                   }
                  }
      }
 
}


