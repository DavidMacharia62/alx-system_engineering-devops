# Web Server and DNS README

## Web Server

### Main Role of a Web Server

A web server is a crucial component of the World Wide Web. Its primary role is to handle incoming HTTP requests from clients (typically web browsers) and serve web content in response to these requests. This content can include HTML pages, images, stylesheets, scripts, and more. Web servers are responsible for processing these requests efficiently, making them a fundamental part of internet infrastructure.

### Child Process

In a computing environment, a child process is a separate process spawned or created by another process, known as the parent process. Child processes are often used in multi-processing systems to perform tasks independently. They inherit certain attributes from the parent process but operate as distinct entities. Child processes can help distribute workloads, enhance system stability, and enable parallel processing.

### Parent and Child Processes in Web Servers

Web servers typically adopt a parent-child process model for improved performance and reliability. Here's how it works:

- **Parent Process (Master Process)**: The parent process is responsible for managing critical server tasks such as listening for incoming connections, handling configuration changes, and overseeing child processes. It ensures that the server operates smoothly and efficiently.

- **Child Processes**: Child processes are created by the parent process to handle actual client requests. These processes work in parallel, allowing the web server to handle multiple client connections simultaneously. If one child process encounters an issue, it does not disrupt the entire server, ensuring robustness and fault tolerance.

## HTTP Requests

### Main HTTP Requests

HTTP (Hypertext Transfer Protocol) defines various types of requests, each serving a specific purpose:

- **GET**: Requests a resource from the server, typically used for retrieving data such as web pages or images.

- **POST**: Submits data to be processed by a specified resource, often used for form submissions.

- **PUT**: Updates a resource on the server with new data.

- **DELETE**: Removes a resource from the server.

- **HEAD**: Requests only the headers of a resource without the actual content, useful for checking resource availability.

- **OPTIONS**: Inquires about the communication options available for a resource.

- **PATCH**: Applies partial modifications to a resource, often used in RESTful APIs for updates.

## DNS (Domain Name System)

### What is DNS?

DNS, or Domain Name System, is a critical component of the internet infrastructure. It serves as a hierarchical, distributed system designed to translate human-readable domain names (e.g., www.example.com) into numerical IP addresses (e.g., 192.168.1.1). DNS enables users and computers to locate resources on the internet using user-friendly domain names.

### DNS Record Types

DNS employs various record types to store specific types of information. Some common DNS record types include:

- **A (Address) Record**: Maps a domain name to an IPv4 address, allowing browsers to find the web server associated with a domain.

- **CNAME (Canonical Name) Record**: Creates an alias or nickname for one domain name to another, often used for subdomains or domain redirection.

- **TXT (Text) Record**: Holds textual information associated with a domain, frequently used for domain verification and DNS-based security measures.

- **MX (Mail Exchanger) Record**: Specifies the mail servers responsible for receiving email for a domain, directing email traffic.

These DNS records play a crucial role in configuring and managing a domain's online presence, ensuring proper resource routing and information retrieval.


