node(){
    stage("clone code"){
        checkout changelog: false, poll: false, scm: scmGit(branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/manjuyadrami/java-tomcat-maven-docker.git']])        print "clone"
    }
      stage("maven build"){
        print "maven"
    }
      stage("upload artifact"){
        print "upload"
    }
    
       stage("deploy to dev"){
        print "deploy"
    }}
