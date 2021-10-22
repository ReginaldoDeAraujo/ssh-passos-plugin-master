node {
  def remote = [:]
  remote.name = 'reginaldo'
  remote.host = 'reginaldo@192.168.1.108 -p 22'
  remote.user = 'reginaldo'
  remote.password = '379223'
  remote.allowAnyHosts = true
  stage('Remote SSH') {
    sshCommand remote: remote, command: "ls -lrt"
    sshCommand remote: remote, command: "for i in {1..5}; do echo -n \"Loop \$i \"; date ; sleep 1; done"
  }
}

