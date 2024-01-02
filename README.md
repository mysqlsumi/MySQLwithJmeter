# MySQLwithJmeter
How to do mysql benchmark test with Jmeter
Jmeter를 이용해서 MySQL DB에 대한 벤치마크 테스트하는 방법에 대해 소개합니다.

## 0. Pre- Requisite (사전작업)
### 1) Download and install Java 8+ on your Jmeter test server such as Window, Mac and etc. (자바 다운로드 및 설치)
[Download java](https://www.java.com/ko/download/)

### 2) Download and install Jmeter. (Jmeter 다운로드 및 설치)
[Download Jmeter](https://jmeter.apache.org/download_jmeter.cgi)


### 3) Down load MySQL Connector and place it in jmeter/ lib folder.(mysql connector를 다운받은 후 Jmeter 라이브러리 디렉토리에 위치)
[Download MySQL Connector](https://www.mysql.com/products/connector/)



## 1. Set all parameters for MySQL testing on Jmeter.(Jmeter에 mysql 설정을 합니다.)
* Select JDBC Connection Configuration (JDBC Connection Configuration 메뉴선택)

![스크린샷 2023-10-24 오전 11 03 07](https://github.com/mysqlsumi/MySQLwithJmeter/assets/31054795/21da65cb-e816-422b-8e1f-7e1df0b213f2)
