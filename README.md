# mybatis


구글링에서 얻어온 설정파일로 하다보니 되게 골머리를 앓았다.

property name="driverClassName" value="com.mysql.cj.jdbc.Driver"/
property name="url" value="jdbc:mysql://127.0.0.1:3306/spring?serverTimezone=UTC"/

해당 두 프로퍼티를 값을 사용하려면 mysql커넥터 8.x 이상을 이용해야한다.
