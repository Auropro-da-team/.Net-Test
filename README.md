# .NET Bing Translate Sample

## Description
This project is a .NET application that uses the Bing translator API. It sends a request to the Azure token server to obtain an OAuth token each time it sends a request to the translator service. The result from that request is then fed into the request sent to the translation service itself.

## Features
- Translates English phrases to Spanish using the Bing translator API.
- Uses an OAuth token obtained from Azure token server for each translation request.
- Handles exceptions and errors during the translation process.

## Installation
1. Clone the repository to your local machine.
2. Open the solution in Visual Studio.
3. Update the `_clientId` and `_clientSecret` fields in the `AccessTokenMessageHandler.cs` file with your Azure application key. You can obtain this key from Azure Marketplace. See [this link](http://msdn.microsoft.com/en-us/library/hh454950.aspx) for details.

## Usage
To run the application, simply press F5 in Visual Studio. The application will translate the phrase "Hello World" from English to Spanish and display the result in the console.

## Technologies Used
- .NET Framework
- C#
- Bing Translator API
- Azure Marketplace Access Token
- HttpClient

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License. See the LICENSE file for details.