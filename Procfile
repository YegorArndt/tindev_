web: cd backend && mvn clean package &&
cd .. &&
cd frontend && npm install && npm run start &&
cd .. && cd backend && java -Dserver.port=$PORT $JAVA_OPTS -jar target/*.jar
