## Web-hacking-LAB
취약한 사이트에 웹해킹을 해보자!
- 취약한 사이트 소스를 서버에 올려 준비하기.
## 정보 수집
- 웹페이지 살펴보기.
> ![image](https://github.com/hanmin0512/Web-hacking-LAB/assets/37041208/8d0f600d-4766-4a66-8785-4e0bd7385673)
- nmap을 통해 사이트의 정보를 파악하기.
> ![nmap](https://github.com/hanmin0512/Web-hacking-LAB/assets/37041208/226cee5c-ec94-4ab2-818d-ec716b1c9b8e)
1. 웹서버는 Microsoft IIS httpd 6.0을 통해 호스팅 하고 있다.

- nikto를 통한 정보 수집.
> ![image](https://github.com/hanmin0512/Web-hacking-LAB/assets/37041208/c35870d6-542d-4b53-9ecf-1d0753c50a12)
1. CVE-2000-0649 취약점이 발견 되었다.

## web-hacking
- 계정정보 추측 및 대입
<table>
  <tr>
    <th>분류</th>
    <th>코드</th>
    <th>점검 항목</th>
  </tr>
  <tr>
    <td rowspan="2">계정정보<br>추측 및 대입</td>
    <td>BP-001</td>
    <td>취약한 패스워드 설정 여부</td>
  </tr>
  <tr>
    <td>BP-002</td>
    <td>어플리케이션/장비 기본 패스워드 설정 여부</td>
  </tr>
</table>

##








