# Bing Translate .NET Sample

## Description
This .NET project is a sample application that demonstrates how to use the Bing Translator API. It sends a request to the Azure token server to obtain an OAuth token each time a request is sent to the translator service. The result from that request is then fed into the request sent to the translation service itself.

## Features
- Utilizes Bing Translator API for translation services.
- Implements OAuth authentication with Azure token server.
- Handles HTTP requests and responses.
- Handles exceptions and errors.

## Installation
1. Clone the repository to your local machine.
2. Open the solution in Visual Studio.
3. Update the `_clientId` and `_clientSecret` fields in `AccessTokenMessageHandler.cs` with your Azure application key. You can obtain an application key from Azure Marketplace. See [here](http://msdn.microsoft.com/en-us/library/hh454950.aspx) for details.
4. Build and run the solution.

## Usage
Run the application. The application will translate the phrase "Hello World" from English to Spanish and output the result to the console.

## Technologies Used
- .NET Framework
- C#
- Bing Translator API
- Azure Marketplace OAuth

## Contributing
To contribute to this project, please submit a pull request with a description of your proposed changes.

## License
This project is licensed under the MIT License.