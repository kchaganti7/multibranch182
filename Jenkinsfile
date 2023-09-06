node('built-in')
{
stage('continuous download')
{
git branch: 'main', url: 'https://github.com/kchaganti7/awsmaven.git'
}
stage('Continuous build')
{
sh 'mvn package'
}
}
