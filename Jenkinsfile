pipeline {
    agent "ba1"
    options { timestamps () }

    stages {
        stage('Renew Auto Scaling') {
            steps {
                renewAutoScalingGroup("jenkins-test", "us-east-1")          
            }
        }
    }
}
