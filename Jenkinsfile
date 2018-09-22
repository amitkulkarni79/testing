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
					input('Do You Want to Proceed')
				}
				stage('three')
				{
					when{
							not 
							{
								branch "master"
							}
						}
							steps
							{
								echo 'Hi This is not master branch'
							}
					
				}
				stage('four')
				{
					parallel{
							stage('Unit Testing')
							{
								steps {
							  
											echo 'Unit testing.......'
								      }
							}
							stage('Integration Testing')
							{
								steps {
							  
											echo 'Running Integration testing.......'
									  }
							}
							
							
							}
				}
		  
		  }
		  
			



}