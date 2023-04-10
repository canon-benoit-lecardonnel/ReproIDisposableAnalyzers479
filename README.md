Reproducer for https://github.com/DotNetAnalyzers/IDisposableAnalyzers/issues/479

Notes

* `global.json` restricts the SDK to a 6.0 version
* In the `csproj` file, warnings are treated as errors
* The build passes in Visual Studio 2022
* The build fails when running `dotnet build`
