# OracleStudy
0115   jdbc
DB에있는 내용을 JAVA로 뺀다.</br>

1.오라클 엔터프라이즈 버전이 아니라 익스프레스 버전으로 JDBC 절차</br>

구글검색 : 메이븐 리포지토리</br>
> 메이븐 리포지토리에서 jdbc검색 > Tomcat JDBC</br>
사용률 보고 제일 많이 쓰는거 사용하면 된다.</br>
에터프라이즈 버전에서는 SID가 XE가아님  SID: ORCL</br>

10-3의 시작 > ORACLE-DB > NET MANAGER > </br>

리스너 > lister> 호스트 >11111111111 </br>

10-3 : D:\app\ez304\product\11.2.0\dbhome_1\NETWORK\ADMIN </br>

listener.ora , tnsnames.ora 파일 txt로 열기</br>

아이피가 일치하는지 확인</br>
    (ADDRESS_LIST =</br>
      (ADDRESS = (PROTOCOL = TCP)(HOST = 192.168.111.103)(PORT = 1521))</br>
    )</br>

이클립스는 ERD없음 플러그인 있긴한데 다른곳에서 에러뜬다.</br>

10-1에서 Oracle(system)생성시</br>
test 실행시 fail 뜰경우 10-3 > WF.MSC 검색 > 인바운드 규칙에 oracle만들었는지 확인</br>
없으면 인바운드 규칙 >오른쪽 클릭 </br>
> 새규칙으로 oracle규칙을 만든다</br>

★JDBCTest.java 작업시</br>
이클립스 상단의 Window > show view > other > Data Management > Data Source Explorer</br>
>open > 이클립스 상단아래에 배치할것</br>

★JDBCTest.java 는 외우거나 복사해서 가지고 다녀라</br>

pstmt의 n = pstmt.executeUpdate(sql);에서 sql빼라</br>
