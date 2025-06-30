# .Net-Test ResponseEntityProcessorSample

## Description
This .NET project demonstrates how to copy a response entity (body) to a local file and perform additional processing on that file asynchronously. It does so by hooking in a HttpMessageHandler that wraps the response entity with one that both writes itself to the output as normal and to a local file.

## Features
- Asynchronous processing of response entity.
- Response entity is written both to the output and a local file.
- Use of HttpMessageHandler to handle response entities.
- Local file is automatically deleted upon completion of processing.

## Installation
1. Clone the repository to your local machine.
2. Navigate to the cloned repository.
3. Open the solution file in Visual Studio.
4. Build the solution.

## Usage
Run the program in Visual Studio. The program will start a local server and issue GET requests. The ResponseEntityHandler will be in action, saving the response in a local file and displaying the file size and name in the console. The file will be deleted automatically after processing.

## Technologies Used
- .NET Framework
- ASP.NET Web API
- C#

## Contributing
Contributions are welcome. Please fork the project and create a pull request with your changes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.