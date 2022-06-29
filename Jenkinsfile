pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('status') {
            steps {
                echo 'hi how r u'
            }
        }
        stage('SCM') {
            steps {
                git 'https://github.com/Akzz123/webapp.git'
            }
        }
    }
}
