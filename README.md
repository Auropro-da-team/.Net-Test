# Bing Translate .NET Sample

## Description
This .NET project is a sample application illustrating the use of the Bing Translator API. The application sends a request to the Azure token server to obtain an OAuth token each time a request is sent to the translator service. The result from the token request is then fed into the request sent to the translation service itself.

## Features
- Translation of English phrases to Spanish.
- Use of Bing Translator API.
- Use of Azure Marketplace Access Token.

## Installation
1. Clone the repository to your local machine.
2. Open the solution in Visual Studio.
3. Before running the sample, you must obtain an application key from Azure Marketplace, and fill in the information in the `AccessTokenMessageHandler` class. See [this link](http://msdn.microsoft.com/en-us/library/hh454950.aspx) for details.

## Usage
Run the application in Visual Studio. The application will translate the English phrase "Hello World" to Spanish and display the translated text in the console.

## Technologies Used
- .NET
- C#
- Bing Translator API
- Azure Marketplace Access Token

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.