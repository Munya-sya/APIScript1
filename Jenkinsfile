pipeline {
    agent any
    stages {
       stage('Download Wso2 API Manager 4.1.0'){
            steps {
                echo "Download the WSO2 API Manager"
                sh 'wget https://github.com/wso2/product-apim/releases/download/v4.1.0-alpha/wso2am-4.1.0-alpha.zip'
                sh 'ls'
            }
       }
    }
}