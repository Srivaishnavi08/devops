pipeline{
    agent any
    stages{
        stage('Git Acess'){
            steps{
                git branch:'main', url:'https://github.com/Srivaishnavi08/devops'
            }
        }
        stage('Java Execution'){
            steps{
                bat 'javac app.java'
                bat 'java app'
            }
        }
        stage('Python execution'){
            steps{
                bat 'python app.py'
            }
        }
    }
}