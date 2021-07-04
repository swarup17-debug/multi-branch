pipeline {
	agent any
    stages {
        stage("Build Master"){
            when{
                buildingTag()
            }
            steps{
                echo "Buiding from tag"
            }
        }
	}
}
