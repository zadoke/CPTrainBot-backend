# CPTrainBot Backend

This is the Rust backend for CPTrainBot, a Discord bot that retrieves train schedules and information from Infrastruturas de Portugal and displays them on Discord.

## Prerequisites

To run the backend of CPTrainBot, you'll need to have Rust installed on your system. You can find instructions on how to install Rust [here](https://www.rust-lang.org/tools/install).

## Installation

To install the backend of CPTrainBot, follow these steps:

1. Clone this repository.
2. Run `cargo build` to build the project.

You can also deploy the backend and frontend using docker compose. Instructions are [here](https://github.com/zadoke/CPTrainBot#installation)

## Running the Backend

To start the backend of CPTrainBot, run `cargo run` in the project root. The backend server will start and expose its API on port 8000.

## Usage

The backend of CPTrainBot is responsible for retrieving train schedules and information from Infrastruturas de Portugal. It communicates with the Discord bot to provide this information to users.

The backend uses a RESTful API to expose several endpoints for retrieving train schedules and information. These endpoints can be accessed by sending HTTP requests to the appropriate URL.

For example, to retrieve information about a specific train, you can send a GET request to the `/train/:trainnumber` endpoint, where `:trainnumber` is the number of the train you want to retrieve information about.

### Endpoints

You can check the current endpoints in the [wiki!](https://github.com/zadoke/CPTrainBot-backend/wiki/Endpoints)

## Contributing

Contributions are welcome! Please feel free to open a pull request or an issue if you have any suggestions or improvements.

## License

This project is licensed under the GNU GPLv3 license. Please refer to the LICENSE file for more information.
