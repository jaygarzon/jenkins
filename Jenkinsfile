node {
    stage('Checkout'){
       scm' https://github.com/jaygarzon/jenkins/tree/master/jenkins'  
    }
    stage('Build') {
        sh './gradlew bootRun'
    }
    stage('Test') {
        echo 'Building....'
    }
    stage('Deploy') {
        echo 'Deploying....'
    }
}
