pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build app'
            }
        }
		stage('Test') {
            steps {
                echo 'Test app'
            }
        }
		stage('Deploy') {
            steps {
                echo 'Deploy app'
            }
        }
    }
	post
		{
		  failure
		  {
		  mail bcc: '', body: 'hello', cc: 'nischithanishu18@gmail.com', from: '', replyTo: '', subject: 'test-jenkins', to: 'asnaveen787@gamil.com'
		  }
		
		}
}
