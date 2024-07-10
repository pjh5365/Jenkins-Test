pipeline {
    agent any
    triggers {
        githubPush()
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                // 여기서 빌드 스크립트를 작성하세요.
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                // 여기서 테스트 스크립트를 작성하세요.
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // 여기서 배포 스크립트를 작성하세요.
            }
        }
    }
}

