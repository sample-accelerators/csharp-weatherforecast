# C# Sample Accelerator

A sample accelerator for C#.

This sample is the Weather Forecast RESTful API application made available from Microsoft.  It provides a single endpoint, `/weatherforecast`, that returns a mock forecast for the upcoming several days.

The starting source for this sample was created using:
```
$ dotnet new webapi --language C#
```

If the _Dockerfile_ option is elected, the generated project will include a Dockerfile that can be used to create a Docker image for the sample application.

To run the sample application:

```
$ dotnet run
```

| URL | Description |
| --- | --- |
| https://localhost:5001/swagger | API Documentation |
| https://localhost:5001/weatherforecast | Weather Forecast Endpoint |

