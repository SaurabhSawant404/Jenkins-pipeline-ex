pipeline{

    agent any
    stages{

        stage("compile"){
            steps{
                sh "javac Test.java"
            }
        }
        stage("run"){
            stage{
                sh "java Test"
            }
        }
    }
}