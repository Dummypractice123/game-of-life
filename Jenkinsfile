node('REDHAT')
{
    stage('scm')
    {
        git 'https://github.com/Dummypractice123/game-of-life.git'
    }
    stage('build')
    {
        sh 'mvn package'
    }
}
