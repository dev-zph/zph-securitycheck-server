FROM 127.0.0.1:5000/zph/java
ADD *.jar /opt/app.jar
# time zone
RUN echo "Asia/Shanghai" > /etc/timezone
ENTRYPOINT ["sh", "-c", "java $JAVA_OPTS -jar /opt/app.jar $EXTRA_PARAM"]
EXPOSE 11000

