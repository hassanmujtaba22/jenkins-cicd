pipeline {
     agent any
     stages {
        stage("Build") {
            steps {
                sh "sudo npm install"
                sh "sudo npm run build"
            }
        }
        stage("Deploy") {
            steps {
                sh "sudo npm start"
                // sh "sudo cp -r jenkins-cicd/build/ /var/www/edudemic/"
                // sh "pm2 start npm --name "next-app" -- start"
            }
        }
    }
}