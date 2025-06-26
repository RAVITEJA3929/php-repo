FROM mysql/mysql-server:5.7

# Environment variables
ENV MYSQL_ROOT_PASSWORD=admin123

# Copy initialization script
COPY init.sql /docker-entrypoint-initdb.d/

