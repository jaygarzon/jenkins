node {
     stage('Build') {
        sh 'cd /Users/jaygarzon/jenkinsLearn/jenkins && gradle clean build'
    }
    stage('Deploy') {
     	sh 'cd /Users/jaygarzon/jenkinsLearn/jenkins && cf push jenkins-app -p build/libs/demo-0.0.1-SNAPSHOT.jar --random-route'
    }
  
}
