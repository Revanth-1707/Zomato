pipeline{
    agent any{
        label 'java_node'
    }
    
    tools{
        maven 'maven'
    }
    
    stages{
        stage('build'){
            steps{
               sh 'mvn clean package' 
            }
        }
    }
}
