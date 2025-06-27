# ps-http-sim: PlanetScale Protocol Simulator Docker Image

This repository only contains the Docker image that simulates the [PlanetScale](https://planetscale.com/) connection protocol using a standard SQL backend. The image fully implements the PlanetScale library interface, making it suitable for development and testing as a PlanetScale-compatible SQL server.

> **Note:** This repository is for the image only. For usage instructions and integration details, please see the main project repository: [ps-http-sim host & usage instructions](https://github.com/example/ps-http-sim-host).

## Image Details
- **Exposes:** PlanetScale-compatible protocol on port 8080
- **Backend:** Standard SQL engine (e.g., MySQL or SQLite, depending on implementation)
- **Compatibility:** Designed to work with official PlanetScale client libraries and tools

## License
This project is licensed under the MIT License. See the `LICENSE` file for details. 