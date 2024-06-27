# Tomcatベースイメージを使用
FROM tomcat:9.0.89-jdk17-corretto-al2

# MySQL JDBCドライバをダウンロードしてコピー
COPY ./jdbc/mysql-connector-j-8.4.0.jar /usr/local/tomcat/bin

# WARファイルをコピー
COPY ./war/BulletBoard.war /usr/local/tomcat/webapps/
