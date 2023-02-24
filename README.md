# hibernate.cfg.xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE hibernate-configuration PUBLIC
	"-//Hibernate/Hibernate Configuration DTD 3.0//EN"
	"http://hibernate.sourceforge.net/hibernate-configuration-3.0.dtd">
<hibernate-configuration>
	<session-factory>
		<property name="hibernate.connection.username">root</property>
		<property name="hibernate.connection.url">jdbc:mysql://localhost:3306/exp1</property>
<!-- 		<property name="hibernate.connection.password">arun</property> -->
		<property name="hibernate.connection.driver_class">com.mysql.jdbc.Driver</property>
		<!-- <property name="hibernate.dialect">org.hibernate.dialect.MySQLDialect</property> -->
		<property name="hibernate.show_sql">true</property>
		<property name="hbm2ddl.auto">update</property> 
		<mapping class="com.jspiders.pakistan.dto.Taliban"></mapping>
	</session-factory>
</hibernate-configuration>
