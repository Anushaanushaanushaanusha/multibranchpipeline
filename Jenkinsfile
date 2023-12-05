pipeline{
    agent any
    stages {
        stage('hotfix updated') {
            steps {
                sh 'echo "this is hotfix changes updated successfully" '
            }
        }
        stage('test') {
            steps {
                sh 'echo "hotfix applicaiton....." '
            }
        }
        stage('deploy application') {
            steps {
                sh 'echo "deploy application........" '
            }
        }
    }
}
