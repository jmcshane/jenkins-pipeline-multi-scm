node('master') {
    dir ('main-repo') {
      checkout scm
    }
    dir('other-repo') {
       git url: 'https://github.com/jmcshane/hubot-taskmaster'
      checkout scm
    }
    sh """ls
    ls main-repo
    ls other-repo"""
}
