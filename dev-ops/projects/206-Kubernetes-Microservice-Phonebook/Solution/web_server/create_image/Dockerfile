FROM python:alpine
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
EXPOSE 80
CMD python app.py



# FROM python:alpine
# COPY requirements.txt .
# RUN pip install -r requirements.txt
# COPY . /app
# WORKDIR /app
# EXPOSE 80
# CMD python app.py


# FROM eclipse-temurin:17-jdk-jammy
# WORKDIR /app
# COPY .mvn/ .mvn
# COPY mvnw pom.xml ./
# RUN ./mvnw dependency:resolve
# COPY src ./src
# CMD ["./mvnw", "spring-boot:run"]
