properties([[$class: 'JobLocalConfiguration', changeReasonComment: ''], pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("clone") {
        git branch: 'main', url: 'https://github.com/DrDrumm911/DevOps2412.git'
    }
    stage("show files"){
        sh "ls -l"
    }
}
