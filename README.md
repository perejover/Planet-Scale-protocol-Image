# ps-http-sim: PlanetScale Protocol Simulator Docker Image

This repository only contains the Docker image that simulates the [PlanetScale](https://planetscale.com/) connection protocol using a standard SQL backend. The image fully implements the PlanetScale library interface, making it suitable for development and testing as a PlanetScale-compatible SQL server.

> **Note:** This repository is for the image only. For usage instructions and integration details, please see the main project repository: [Planet-Scale-Protocol-with-SQL-DB](https://github.com/perejover/Planet-Scale-Protocol-with-SQL-DB).

## Image Details
- **Exposes:** PlanetScale-compatible protocol on port 8080
- **Backend:** Standard SQL engine (e.g., MySQL or SQLite, depending on implementation)
- **Compatibility:** Designed to work with all official PlanetScale client libraries and tools
