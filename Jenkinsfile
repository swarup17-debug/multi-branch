pipeline {
	agent any
    stages {
        stage("Build Master"){
            when{
                branch 'main'
            }
            steps{
                echo "Deploying master branch"
            }
        }
        stage("Build Dev"){
            when{   
                branch 'dev'
            }
            steps{
                echo "Deploying Dev branch"
            }
        }
    }

}
