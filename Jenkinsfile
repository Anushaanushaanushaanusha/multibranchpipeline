pipeline{
    agent any
    stages {
        stage('hotfix') {
            steps {
                sh 'echo "this is hotfix changes" '
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
