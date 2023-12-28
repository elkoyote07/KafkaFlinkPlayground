<img src="KafkaFlinkPlaygroundImage.png" alt="KafkaFlinkPlayground logo" width="600" height="600">  

# Kafka Flink Playground&nbsp;

A friendly playground for experimenting with Kafka and Flink integration and development.

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/elkoyote07/KafkaFlinkPlayground?tab=MIT-1-ov-file)

## Overview

Briefly describe what your project is about. Highlight the main features and use cases. Mention the technologies it involves, such as Kafka, Flink, and Apache.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

To get started with this project, follow these steps:

### Prerequisites

- [Docker](https://www.docker.com/) installed on your machine.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/elkoyote07/KafkaFlinkPlayground.git
   cd KafkaFlinkPlayground
   ```
   
2. Set the necessary permissions for config.yml:

   ```bash
   chmod 777 config.yml
   ```
   The above command grants full permissions to config.yml, allowing Kafka UI to save configuration data to the volume.

## Usage

1. Start the services using Docker Compose:

   ```bash
   docker-compose up -d
   ```
After successfully setting up the project, you can access the following web interfaces:

- **Kafka UI**: Visit [http://localhost:8080](http://localhost:8080) to explore and manage your Apache Kafka topics using the Kafka UI.

- **Flink Dashboard**: Access the Flink Dashboard at [http://localhost:8081](http://localhost:8081) to monitor and manage your Flink jobs and clusters.

Additionally, the Kafka server is running on port 9093. You can configure your Kafka clients to connect to this server for producing and consuming messages.

## Contributing

We welcome and appreciate contributions from everyone. Whether you're fixing a bug, improving documentation, or adding a new feature, your input is valuable.

## Reporting Issues

If you encounter any issues or have suggestions, please open an issue with a clear description of the problem or enhancement you're proposing.

## License

This project is licensed under the [MIT License](https://github.com/elkoyote07/KafkaFlinkPlayground?tab=MIT-1-ov-file).

### Third-Party Licenses

This project incorporates software with the Apache-2.0 license.

#### Apache-2.0 Licensed Software

- [wurstmeister/kafka](https://github.com/wurstmeister/kafka-docker?tab=Apache-2.0-1-ov-file#readme)
- [apache/flink](https://github.com/apache/flink/blob/master/LICENSE)
- [provectuslabs/kafka-ui](https://github.com/provectus/kafka-ui/blob/master/LICENSE)

Please ensure compliance with the licensing terms of the Apache-2.0 licensed software when using or contributing to this project.



