pipeline {
	agent any
    stages {
        stage("Build Master"){
            when{
                buildingTag()
            }
            steps{
                echo "buiding from tag"
            }
        }
	}
}

