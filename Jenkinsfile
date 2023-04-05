pipeline {
	agent  {
    docker {
        image 'hello-world'
        
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

