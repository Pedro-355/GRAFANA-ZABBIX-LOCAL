FROM zabbix/zabbix-server:latest

COPY config/zabbix_server.conf /etc/zabbix/zabbix_server.conf

EXPOSE 10051

CMD ["zabbix_server", "-f"]