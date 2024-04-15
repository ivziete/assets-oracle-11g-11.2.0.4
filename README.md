# oracle-11g-11.2.0.4

docker-compose.yml

    version: '3'
    services:
      db:
        image: ivancondori/oracle-11g-11.2.0.4
        hostname: oracle-docker
        ports:
        - "1521:1521"
        volumes:
        - ./install:/install
        - ./app:/opt/oracle/app
        - ./dpdump:/opt/oracle/dpdump
        privileged: true
# assets-oracle-11g-11.2.0.4
# assets-oracle-11g-11.2.0.4
# assets-oracle-11g-11.2.0.4
