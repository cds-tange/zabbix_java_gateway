H.Tange 2016/06/16
  WildFlyをZabbixのJMX監視で監視できるようにするために、ZabbixのJava Gatewayを改修した。
  改修方針は、Propertiesファイル中に登録されているIPアドレスリストに対しては、WildFly用
  のJMX URLを使用するように改修した。

  Java Gatewayをインストールした後にjboss-cli-client.jarを/usr/sbin/zabbix_java/libにコ
  ピーする。