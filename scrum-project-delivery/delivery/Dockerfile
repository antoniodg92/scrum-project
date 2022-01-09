FROM jboss/wildfly:14.0.0.Final

COPY deployments  /opt/jboss/wildfly/standalone/deployments/

USER root

RUN chmod -R 777 /opt/jboss/wildfly/standalone/deployments/

RUN chmod g+rwx /opt/jboss/wildfly/standalone/tmp/auth