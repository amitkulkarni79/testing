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
			  stage('three')
			  {
			  	  when 
					{ 
						branch 'master' 
					}
    					steps 
					{ 
       						 echo 'I only execute on the master branch.' 
   					}
				  
								  
		 		}
			  
		  }
				

}
