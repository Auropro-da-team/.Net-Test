# BingTranslate.NET

## Description
BingTranslate.NET is a .NET project that demonstrates the use of the Bing Translator API. The API requires an OAuth token which is obtained by sending a request to the Azure token server each time a request is sent to the translator service. The result from that request is fed into the request sent to the translation service itself.

## Features
- Translates English phrases to Spanish using the Bing Translator API.
- Uses an OAuth token obtained from Azure token server for authentication.
- Displays the translated text in the console.

## Installation
1. Clone the repository to your local machine.
2. Open the solution in Visual Studio.
3. Replace the `_clientId` and `_clientSecret` fields in `AccessTokenMessageHandler.cs` with your Azure Marketplace application key. See [here](http://msdn.microsoft.com/en-us/library/hh454950.aspx) for details on obtaining an application key.
4. Build the solution.

## Usage
Run the application in Visual Studio. The application will translate the phrase "Hello World" from English to Spanish and display the translated text in the console.

## Technologies Used
- .NET Framework
- C#
- Bing Translator API
- Azure Marketplace Access Token

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.