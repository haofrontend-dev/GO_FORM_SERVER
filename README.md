## Go send form basic
# Demo Server

This is a simple server written in Go that serves static files and handles two routes: `/hello` and `/form`. The `/hello` route responds to GET requests with the message "hello". The `/form` route handles POST requests and retrieves the values of the `name` and `email` fields from the form data.

## Prerequisites

- Go installed on your machine

## Installation

1. Clone this repository to your local machine.
2. Open a terminal and navigate to the project directory.
3. Run the following command to install the required dependencies:

## Usage

1. Start the server by running the following command:

2. The server will start running on port 8080. You can access it at `http://localhost:8080`.

### `/hello`

- This route responds to GET requests.
- It returns the message "hello".

### `/form`

- This route handles POST requests.
- It expects form data with the following fields:
- `name`: The name of the user.
- `email`: The email address of the user.
- It returns a response with the message "POST request successful" and the values of the `name` and `email` fields.

## Static Files

The server serves static files from the `./static` directory. You can add your own static files to this directory.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please submit a pull request or open an issue.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.