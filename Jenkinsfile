@Library('jenkins-library@master') _
 
pipeline {
    agent any
    stages {
        stage('Git Checkout') {
            steps {
            gitCheckout(
                branch: "master",
                url: "https://github.com/Manju-G/jenkins-shared-library-framework.git"
            )
            }
    }
    }
}
