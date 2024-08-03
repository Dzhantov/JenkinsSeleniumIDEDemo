pipeline{
    agent any

    stages{
        stage("Checkout code"){
            //checkout the repository
            steps{
                git branch: 'main', url: 'https://github.com/Dzhantov/JenkinsSeleniumIDEDemo.git'
            }
        }
        stage("Setup .Net core"){
            //install dotnet
        }
        stage("Restore dependencies"){
            //install dependencies
        }
        stage("Build"){
            //build
        }
        stage("Run tests"){
            //run tests
        }
    }
}