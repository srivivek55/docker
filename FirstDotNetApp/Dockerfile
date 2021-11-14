FROM mcr.microsoft.com/dotnet/aspnet:5.0 AS runtime
WORKDIR /app
COPY FirstDotNetApp.dll ./
ENTRYPOINT ["dotnet", "FirstDotNetApp.dll"]