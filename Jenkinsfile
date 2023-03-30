pipeline {
	agent  {
    docker {
        image 'maven:3.9.0-eclipse-temurin-11'
        label 'my-defined-label'
        args  '-v /tmp:/tmp'
    }
}
			stages{
				stage('Build')
			{
			steps 
			{
				echo "Building hello"
				
			}
		}
	stage('Test')
		{
		steps
		{
			echo "testing hello"
		}
	}
	stage('Deploy')
	{
	steps
	{
	 echo "Deploying hello"
	}
	}
}
}

