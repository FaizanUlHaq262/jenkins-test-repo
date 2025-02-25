pipeline{
    agent any
    stages{
        stage('checkout the repo'){
            steps{
                git branch:"main", url:'https://github.com/FaizanUlHaq262/jenkins-test-repo.git'
            }
        }

        stage('creating a new file'){
            steps{
                echo "Creating a new file..."
                bat 'echo. > myFile.txt'
                echo "File created...."
            }
        }
    }
}