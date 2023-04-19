# Use the official Golang image as the base image
FROM golang:1.18

# Set the working directory
WORKDIR /app

# Clone the repository
RUN git clone https://github.com/iamf-dev/scheduler0.git .

# Build the binary
RUN go build -o scheduler0

# Start the program
CMD ["/app/scheduler0" , "start"]
