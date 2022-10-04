pipeline
{
	agent 
	{
		label
		{

			label 'built-in'
			customWorkspace '/data/test'
		
		}
	}
	stages
		{
		stage('touch')
		{
			steps
			{
			echo "pipeline Demo"
			sh "touch 1 2 3 4"
			}
		}
	    }
	
}
