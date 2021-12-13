#See https://aka.ms/containerfastmode to understand how Visual Studio uses this Dockerfile to build your images for faster debugging.
#satdevemltest.azurecr.io/testimg:v1 mcr.microsoft.com/dotnet/runtime:6.0
FROM mcr.microsoft.com/dotnet/runtime:6.0
WORKDIR /app
EXPOSE 80
EXPOSE 443

# FROM base AS final
# WORKDIR /app
COPY /bin/Release/net6/publish .
ENTRYPOINT ["dotnet", "SampleConsoleNet5.dll"]