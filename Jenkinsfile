pipeline{
    agent any
    tools
    {
        maven "MAVEN-3.9"
    }
    stages{
        stage ('Build'){
            agent{
                    label 'java-slave'
            }
            echo "***********This is Build stage************"
        }
    }
}
