# ResponseEntityProcessorSample

## Description
This .NET project demonstrates how to copy a response entity (body) to a local file and perform additional processing on that file asynchronously. It does so by hooking in a `HttpMessageHandler` that wraps the response entity with one that both writes itself to the output as normal and to a local file.

## Features
- Asynchronous processing of HTTP response bodies
- Writing HTTP response bodies to local files
- Customizable `HttpMessageHandler` for response processing
- Self-hosted HTTP server with custom routing

## Installation
1. Clone the repository to your local machine.
2. Navigate to the cloned directory.
3. Open the solution file `ResponseEntityProcessorSample.sln` in Visual Studio.
4. Build the solution (Ctrl+Shift+B).

## Usage
1. Run the program from Visual Studio (Ctrl+F5).
2. The server will start and listen on `http://localhost:50231/`.
3. The server will issue GET requests and process the responses.
4. Press ENTER to stop the server.

## Technologies Used
- .NET Framework
- ASP.NET Web API
- C#

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.