
node {
  def remote = [:]
  remote.name = 'reginaldo-C14CR21TV'
  remote.host = 'reginaldo@192.168.1.108'
  remote.user = 'root'
  remote.password = '379223'
  remote.allowAnyHosts = true  
  stage('Remote SSH') {
    sshCommand remote: remote, comand: "ls -lrt"
  }
}
