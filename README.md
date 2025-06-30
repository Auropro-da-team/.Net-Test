# .NET Bing Translate Sample

## Project Title
.NET Bing Translate Sample

## Description
This project is a sample application that demonstrates how to use the Bing Translator API in a .NET application. It uses an OAuth token obtained from the Azure token server to send a request to the translator service. The response from the translator service is then used to translate a given text from English to Spanish.

## Features
- Uses Bing Translator API for translation
- Utilizes Azure Marketplace Access Token for authentication
- Asynchronous HTTP requests
- Exception handling for request failures

## Installation
1. Clone this repository to your local machine.
2. Open the solution in Visual Studio.
3. Update the `_clientId` and `_clientSecret` fields in the `AccessTokenMessageHandler.cs` file with your Azure Marketplace application key.
4. Build and run the solution.

## Usage
Once the application is running, it will translate the phrase "Hello World" from English to Spanish using the Bing Translator API. The translated text will be displayed in the console.

## Technologies Used
- .NET Framework
- C#
- Bing Translator API
- Azure Marketplace Access Token
- HttpClient
- Newtonsoft.Json

## Contributing
Contributions are welcome. Please open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.