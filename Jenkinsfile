
node{
  checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[ url: 'https://github.com/rahulraj2/github-api-global-lib.git']]])
  load 'CIJenkinsfile'
}
