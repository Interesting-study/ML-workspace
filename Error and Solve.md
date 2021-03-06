## 머신러닝 공부하면서 발생한 에러와 그 해결법

<br>
<br>

 * > zsh: command not found: virtualenv
    * 원인 : 기본 접근법이 통하지 않았음
        * 해결법 : python3 -m virtualenv env


<br>
<br>


 * > URLError: <urlopen error [SSL: CERTIFICATE_VERIFY_FAILED] certificate verify failed: unable to get local issuer certificate (_ssl.c:1122)>
     * 원인 : ssl 보안 이슈가 발생해서 접속 불가
         * 해결법 :  pip3 install --upgrade certifi >> 이후에 mac에서 python "Install Certificates.command"을 실행함
