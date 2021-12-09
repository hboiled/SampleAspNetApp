
FROM mcr.microsoft.com/dotnet/runtime:5.0
WORKDIR /app
EXPOSE 80
EXPOSE 443

# FROM base AS final
# WORKDIR /app
COPY /bin/Release/net5.0/ref .
ENTRYPOINT ["dotnet", "SampleConsoleNet5.dll"]