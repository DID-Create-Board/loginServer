

해당 코드에 security vulnerabilities 발견되어 일부 repo 정리합니다. 양해바랍니다.
CVE-2021-23337

# loginProject
config파일 아래 config.js을 만들어서 사용하여야 합니다.

module.exports={
  server_port:port_number
  db_url:db_number:portnumber/database_name    };

npm init -y을 package.json을 만든다.
npm install -s을 통해 패키지를 다운받는다.
node server.js을 통해 서버를 실행한다. 
