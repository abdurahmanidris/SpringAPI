FROM postgres

# Copy SQL script into the container
COPY init.sql /docker-entrypoint-initdb.d/

# Environment variables
ENV POSTGRES_DB springapi_db
ENV POSTGRES_USER springapi_user
ENV POSTGRES_PASSWORD 12345