pipeline{
    agent any
    tools
    {
        Maven "MAVEN-3.9"
    }
    stages{
        stage ('Build'){
            agent{
                label 'java-slave'
            }
            steps{
             echo "***********This is Build stage************"
            }
           
        }
    }
}