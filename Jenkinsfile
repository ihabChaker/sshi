pipeline {
  agent any
  stages {
    stage('mm') {
      steps {
        slackSend(baseUrl: 'https://hooks.slack.com/services/', blocks: '.', attachments: ',', channel: 'tp-7', sendAsText: true, message: 'message', token: 'T01T1LSFUV7/B01SP33499Q/IVdIEMaZJiguOqF8ELgV7t2p', username: 'iheb chaker BENAKCHA')
      }
    }

  }
}