pipeline{
    agent any
    stages{
        stage ('Main') {  
            steps {
                echo '*** Main Branch***' 
            }
        }
        post {
            success {
                echo "** success ***"
            }
            failure {
                echo "***Failure"
            }
            always {
                echo "*always*"
            }
        }
}
}
