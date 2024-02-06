node('built-in') 
{
    stage('Continuous Download_devlopment') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_development') 
	{
    sh label: '', script: 'mvn package'
}

