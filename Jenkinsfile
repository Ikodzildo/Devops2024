properties([pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("clone") {
        git branch: 'master', url: 'https://github.com/Ikodzildo/Devops2024.git'
    }
    stage("show files"){
        sh "ls -l"
    }
}
