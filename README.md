# Project Title
.NET Bing Translate Sample

# Description
This is a sample .NET project illustrating the use of the Bing Translator API. The API requires an OAuth token which is obtained by sending a request to the Azure token server each time a request is sent to the translator service. The result from that request is fed into the request sent to the translation service itself.

# Features
- Translates English phrases into Spanish using the Bing Translator API.
- Demonstrates the use of Azure Marketplace Access Token.
- Uses HttpClient for sending asynchronous requests to the Bing translation API.

# Installation
1. Clone the repository to your local machine.
2. Open the solution in Visual Studio.
3. Before running the sample, you must obtain an application key from Azure Marketplace and fill in the information in the AccessTokenMessageHandler class. See http://msdn.microsoft.com/en-us/library/hh454950.aspx for details.

# Usage
1. Run the application in Visual Studio.
2. The application will translate the English phrase "Hello World" into Spanish and output the result in the console.

# Technologies Used
- .NET Framework
- C#
- Bing Translator API
- Azure Marketplace Access Token

# Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

# License
This project is licensed under the MIT License.