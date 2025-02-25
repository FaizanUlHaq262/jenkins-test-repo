pipeline{
    agent any
    stages{
        stage('checkout the repo'){
            steps{
                git branch:"main", url:'https://github.com/FaizanUlHaq262/jenkins-test-repo.git'
            }
        }

        stage('print statement'){
            steps{
                echo "Working till here boss hahaha...."
            }
        }
    }
}