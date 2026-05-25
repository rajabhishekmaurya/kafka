FROM apache/kafka:4.0.0

COPY mm2.properties /opt/kafka/config/mm2.properties

COPY connect/mirror/build/libs/connect-mirror-4.0.0.jar /opt/kafka/libs/

COPY connect/mirror-client/build/libs/connect-mirror-client-4.0.0.jar /opt/kafka/libs/