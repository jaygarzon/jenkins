node {
    
    stage('Build') {
        sh cd '/Users/jaygarzon/jenkinsLearn/jenkins'
        sh 'gradle clean build'
    }
    stage('Test') {
        echo 'build/libs/demo-0.0.1-SNAPSHOT.jar'
    }
    stage('Deploy') {
        echo 'Deploying....'
    }
}
