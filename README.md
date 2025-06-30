# Bing Translate .NET Sample

## Project Title
Bing Translate .NET Sample

## Description
This project is a .NET sample application that demonstrates how to use the Bing Translator API. The application sends a request to the Azure token server each time it sends a request to the translator service. The result from that request is fed into the request sent to the translation service itself.

## Features
- Translates English phrases to Spanish using Bing Translator API
- Demonstrates the use of Azure Marketplace Access Token in the message path
- Handles exceptions and displays the error message

## Installation
To install this project, you need to clone the repository and build the project using Visual Studio or any .NET compatible IDE.

## Usage
Before you can run this sample, you must obtain an application key from Azure Marketplace, and fill in the information in the AccessTokenMessageHandler class. See http://msdn.microsoft.com/en-us/library/hh454950.aspx for details.

## Technologies Used
- .NET Framework
- C#
- Bing Translator API
- Azure Marketplace Access Token

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.