node ("master")
{
stage("Checkout")
{
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '52594f0a-847f-44b2-b266-814604dbbdfc', url: 'https://github.com/midhunkunduru/multibranch_3.git']]])
        sh 'ls -ltr'
        sh 'chmod 777 test.sh'
        sh './test.sh'


}
}
