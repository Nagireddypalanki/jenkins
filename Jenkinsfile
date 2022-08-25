pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                git url: 'https://github.com/Nagireddypalanki/jenkins.git', branch: 'main'
                sh "chmod +x -R ./helloworld.sh"
                sh "./helloworld.sh"
            }
        }
    }
}
