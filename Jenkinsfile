pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                 sh "yum install httpd -y" 	
                sh "systemctl start httpd" 
                                    sh "echo 'this is my pipelinejob' >> /var/www/html/index.html"
                                    sh "chmod 777  /var/www/html/index.html"
            }
        }
    }
}
