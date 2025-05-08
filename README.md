
# Webserver

A minimalist HTTP web server implemented in C++, developed as part of the École 42 curriculum.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Dependencies](#dependencies)
- [Examples](#examples)
- [Troubleshooting](#troubleshooting)
- [Contributors](#contributors)
- [License](#license)

## Introduction

This project involves creating a web server in C++, handling HTTP requests and responses.
It serves as an educational exercise to understand the inner workings of web servers and network programming.

## Features

- Handles basic HTTP requests
- Serves static files
- Customizable configuration
- Logging capabilities
- Support for multiple connections

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/ciusca42/Webserver.git
   cd Webserver
   ```

2. **Build the project:**

   ```bash
   make
   ```

## Usage

After building the project, you can run the server using:

```bash
./webserver [configuration_file]
```

If no configuration file is provided, the server will use default settings.

## Configuration

The server can be configured using a configuration file.
An example configuration file is provided in the `config` directory.
The configuration allows you to set parameters such as:

- Server port
- Root directory for serving files
- Logging options
- Error pages

Ensure that the configuration file is properly formatted and accessible by the server.

## Dependencies

The project is implemented in C++ and uses standard libraries.
No external dependencies are required.

## Examples

To test the server, you can use tools like `curl` or a web browser:

```bash
curl http://localhost:8080
```

Ensure that the server is running and listening on the specified port.

## Troubleshooting

- **Port already in use:** Ensure that the port specified in the configuration is not being used by another application.
- **Permission denied:** Check that you have the necessary permissions to access the specified root directory and files.
- **Configuration errors:** Ensure that the configuration file is correctly formatted and all paths are valid.

## Contributors

- [ciusca42](https://github.com/ciusca42)

## License

This project is licensed under the MIT License.
See the [LICENSE](LICENSE) file for details.
