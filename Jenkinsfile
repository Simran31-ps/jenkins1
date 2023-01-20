pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
        stage('Simran'){
            steps {
                echo "Simran is racing...."
            }
        }
    }
  post{
    always{
  emailext body: 'hello', replyTo: 'simranferoz31@gmail.com', subject: 'Simran', to: 'simranferoz31@gmail.com'
}
  }
}
