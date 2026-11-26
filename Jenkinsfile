pipeline{
    agent any
    stages{
        stage("Stage1"){
            steps{
                echo "Entering Stage1"
            }
        }
        stage("Stage2"){
            steps{
                dotnet build
                dotnet run
            }
        }
    }
}