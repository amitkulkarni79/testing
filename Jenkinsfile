pipeline
{
	agent any
		  stages
		  {
		  
				stage('one')
				{
					steps
					{
					echo 'Hi, This is Amit from citi wannted to learn Jenkins CI/CD pipeline'
				}   }
				stage('two')
				{
					steps
					{
					input('Do You Want to Proceed')
					}
				}
			  stage('Three')
			  {
			  steps
			  	{
				  when
				   {
				    branch "master"
				  }
				  step
				  {
				  	echo 'we are in master branch'
				  }			  
		 		}
			  }
		  }
				

}
