pipeline{
    agent{
        label 'java-slave'
    }
    tools{
        maven 'MAVEN-3.9'
    }
    stages{
        stage ('Build'){
            steps{
                  echo "*******Build***********"
            }
        }
        stage ('Code Quality'){
            steps{
                  echo "*******Code quality***********"
            }
        }
        stage ('Docker Build'){
            steps{
                  echo "*******Docker Build***********"
            }
        }
        stage ('Deploy'){
           steps{
                  echo "*******Deployed***********"
            }
        }
    }
}