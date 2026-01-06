# dotnet-blazor-build-error
Reproduction of a build error with Blazor WASM

1. Run `dotnet new blazorwasm`
2. In CI, install WASM tools: `dotnet workload install wasm-tools`
3. In CI, try to publish: `dotnet publish dotnet-blazor-build-error.csproj -c Release --output publish`