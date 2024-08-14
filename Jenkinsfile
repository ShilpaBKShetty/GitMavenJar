pipeline{
    agent any 
    tools{
        maven 'maven'
    }
    
    stages{
        stage('src_code'){
            steps{
                git 'https://github.com/ShilpaBKShetty/GitMavenJar.git'
            }
        }
        
        stage('clean'){
            steps{
                sh 'mvn clean'
            }
        }
    }
}
