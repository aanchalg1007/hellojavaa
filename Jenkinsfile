pipeline {
    agent any

    triggers {
        githubPush()
    }
    
    stages{
        
        stage('Build') {
            steps {
                echo 'Build the application'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Deploying the application'
            }
        }        
    }
}
