node('built-in') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/himaja-20/mycode.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
	}

