node
{
    stage('checkout')
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'GitHub', url: 'https://github.com/SnehaTimancherla/demo1.git']]])
    }
    stage('Static code')
    {
        echo "stattic"
    }
    stage('Build')
    {
        echo "build"
    }
    stage('test')
    {
        echo "test"
    }
    
    
}
