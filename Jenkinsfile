node('master') {
    dir ('main-repo') {
      checkout scm
    }
    dir('other-repo') {
       git url: 'https://github.com/jmcshane/hubot-taskmaster'
    }
    sh """ls
    ls main-repo
    ls other-repo"""
}
