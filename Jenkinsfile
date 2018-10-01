node{
    stage('Checkout')
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/Devopsforum/webapp.git']]])
        def workspace
    }
    stage('analysis'){
        echo "stage analysis"
    }
}
