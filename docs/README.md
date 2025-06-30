# ResponseEntityProcessorSample

## Description

This .NET project illustrates how to copy a response entity (body) to a local file and perform additional processing on that file asynchronously. It does so by hooking in a `HttpMessageHandler` that wraps the response entity with one that both writes itself to the output as normal and to a local file.

## Features

- Asynchronous processing of HTTP response entities.
- Response entities are saved to a local file for additional processing.
- Custom `HttpMessageHandler` for handling response entities.
- Uses `HttpSelfHostServer` for creating a self-hosted web server.

## Installation

1. Clone the repository to your local machine.
2. Navigate to the cloned repository.
3. Open the solution file `ResponseEntityProcessorSample.sln` in Visual Studio.
4. Build the solution by clicking `Build -> Build Solution`.

## Usage

1. Run the application by clicking `Debug -> Start Debugging`.
2. The application will start a server at `http://localhost:50231/` and listen for incoming HTTP requests.
3. To test the application, you can send HTTP requests to `http://localhost:50231/api/values`.

## Technologies Used

- .NET Framework
- ASP.NET Web API
- C#

## Contributing

1. Fork the project.
2. Create your feature branch: `git checkout -b feature/AmazingFeature`.
3. Commit your changes: `git commit -m 'Add some AmazingFeature'`.
4. Push to the branch: `git push origin feature/AmazingFeature`.
5. Open a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.