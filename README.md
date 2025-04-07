# PingAPI

This is a simple study project that demonstrates a basic REST API created in Lazarus using the Horse framework. The API responds to a `GET` request at the `/ping` endpoint with a `Pong` message.

## Requirements

- Lazarus (with Delphi Mode)
- Horse framework

## Installation

1. Clone the repository or download the source code.
2. Make sure you have the Horse framework installed in your Lazarus environment. You can install it via [Horse GitHub](https://github.com/HashLoad/Horse).
3. Open the `PingAPI.lpr` project in Lazarus.

## Usage

1. Compile the project.
2. The server will start listening on port `9000`.

### API Endpoints

- **GET /ping**: Responds with `Pong`.

## Example

To test the API, run the program and use any HTTP client to send a `GET` request to `http://localhost:9000/ping`. You should receive the following response:

```text
Pong
