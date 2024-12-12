# Use a lightweight base image
FROM alpine:latest

# Set a working directory
WORKDIR /app

# Copy a simple script
COPY hello.sh /app/hello.sh

# Ensure the script is executable
RUN chmod +x /app/hello.sh

# Set the default command
CMD ["/app/hello.sh"]
