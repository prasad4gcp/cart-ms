pipeline{
    agent any
    tools
    {
        Maven "MAVEN-3.9"
    }
    stages{
        stage ('Build'){
            agent{
                node{
                    label 'java-slave'
                }
            }
            echo "***********This is Build stage************"
        }
    }
}