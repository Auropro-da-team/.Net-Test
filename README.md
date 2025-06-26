}
            return result;
        }

        private int GetNext()
        {
            lock (_thisLock)
            {
                return _random.Next(10);
            }
        }
    }
}

---

# ResponseEntityProcessorSample

This.NET project demonstrates how to copy a response entity (body) to a local file and perform additional processing on that file asynchronously.

## Description

The project showcases a `ResponseEntityHandler` that wraps the response entity with one that both writes itself to the output as normal and to a local file. This allows for asynchronous processing of the response entity after it has been copied to a local file.

## Features

*   Copies response entity to a local file
*   Performs additional processing on the local file asynchronously
*   Uses a custom `ResponseEntityHandler` to wrap the response entity
*   Demonstrates usage of `HttpContentProcessor` to process the response entity

## Installation

1.  Clone the repository
2.  Install required NuGet packages (e.g., Microsoft.AspNet.WebApi.Client)
3.  Run the project

## Usage

1.  Start the web server
2.  Use an HTTP client (e.g., Fiddler) to send GET requests to the API
3.  Observe the response entities being copied to local files and processed asynchronously

## Technologies Used

*  .NET Framework
*   ASP.NET Web API
*   C#
*   System.Net.Http

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See LICENSE.txt for details.