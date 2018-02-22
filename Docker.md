yarn export
docker build -t snowflake:v1 .
docker run -d -p 8080:80 snowflake
