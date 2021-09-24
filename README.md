# TRON-NODE
 como desplegar un nodo de tron facil

# debes tener 

+ java

# Descargar FullNode.jar

[FullNode.jar](https://github.com/tronprotocol/java-tron/releases/download/GreatVoyage-v4.3.0/FullNode.jar)

# comando

`nohup java -Xmx24g -XX:+UseConcMarkSweepGC -jar FullNode.jar -c main_net_config.conf </dev/null &>/dev/null &`
