# WebServer with Multi-Thread Support

Welcome to SimpleWebServer, a Java-based web server with multi-thread support. This project allows for concurrent handling of client requests through a thread-per-request mechanism, enabling efficient processing and scalability.

## Table of Contents

- [Introduction](#introduction)
- [Build and Run](#build-and-run)
- [Contribution](#contribution)

## Introduction

SimpleWebServer is designed to handle multiple client requests concurrently by starting a new thread for each incoming request. It provides a straightforward way to run a web server and test it with HTML pages.

## Build and Run

Follow the steps below to build and run the SimpleWebServer:

1. Clone the repository:

    ```bash
    git clone https://github.com/joaosf7/simple-web-server-multi-client.git
    cd simple-web-server-multi-client
    ```

2. Build the project using Maven:

    ```bash
    mvn clean package
    ```

3. Run the JAR file:

    ```bash
    java -jar target/simple-web-server-multi-client-1.0-SNAPSHOT.jar
    ```

4. Open your favorite web browser and navigate to `http://localhost:8085` or use the IP address where the web server is being tested.

## Contribution

If you'd like to contribute to this project, your contributions are welcome! Feel free to open issues, submit pull requests, or provide any suggestions.

## Thank You

Thank you for checking out this project! Your feedback is highly appreciated.

Happy coding!
