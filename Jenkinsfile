pipeline {
	agent any

	
	stages
	{
		stage ("Git clone/scm checkout")
		{
git 'https://github.com/ANKITSHARAF1808/sample-helloworld-Ant.git'
		}
		}
{
stage ("ant build")
{
  steps
  {
  
		withAnt(installation: 'Ankit_Local_Ant') 
		{
		sh 'ant install'
    }
}
}
}
		
		}
