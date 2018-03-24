FROM hypriot/rpi-java

ADD target/strom-dashboard.jar /opt/strom-dashboard.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "/opt/strom-dashboard.jar"]