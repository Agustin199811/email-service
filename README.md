# Email Service for E-commerce Application

This project is an Email Service for an e-commerce application. The Email Service is designed to send authentication tokens to users, allowing them to validate their accounts. By centralizing email delivery, it ensures that user validation processes are consistent and reliable across the e-commerce platform.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Running the Service](#running-the-service)
- [Contributing](#contributing)
- [License](#license)

## Overview

The Email Service is a RESTful API built using Spring Boot. It provides endpoints for sending emails containing authentication tokens to users. This service integrates with other microservices to facilitate the user validation process by sending token-based validation emails.

## Features

- **Send Token Emails:** Allows sending emails to users with authentication tokens for account validation.

## Prerequisites

- Java 17 or higher
- Maven 3.6.3 or higher
- Spring Boot 3 or higher

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/yourusername/email-service.git
    cd email-service
    ```

2. Build the project using Maven:

    ```sh
    mvn clean install
    ```

## Configuration

The configuration for the Email Service is located in `src/main/resources/application.properties`. Below is an example configuration:

```properties
spring.mail.host=smtp.your-email-provider.com
spring.mail.port=587
spring.mail.username=your-email@example.com
spring.mail.password=your-email-password
spring.mail.properties.mail.smtp.auth=true
spring.mail.properties.mail.smtp.starttls.enable=true
```

## Running the Service

To run the service registry, use the following command:

 ```sh
    mvn spring-boot:run
```

## Contributing

Contributions are welcome! If you would like to contribute to this project, please send us an email at
`toapantaagustin9c@gmail.com` with details about your proposed changes or improvements. We look forward to hearing from you!

## License

This project is licensed under the MIT License - see the LICENSE file for details.
