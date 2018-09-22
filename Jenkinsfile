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
			  
				  when 
					{ 
						branch 'master' 
					}
    					steps 
					{ 
       						 echo 'I only execute on the master branch.' 
   					}
				  
					when { 
						not 
						{ 
							branch 'master'
						} 
					}
					steps
				  	{
				  	echo 'we are not in master branch'
				  	}			  
		 		}
			  
		  }
				

}
