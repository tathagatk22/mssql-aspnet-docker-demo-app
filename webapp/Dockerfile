FROM microsoft/aspnetcore-build:1.1.11-1.1.12

COPY . /app

WORKDIR /app

RUN ["dotnet", "clean"]

RUN ["dotnet", "restore"]

RUN ["dotnet", "build"]

EXPOSE 80

ENTRYPOINT ["C:/app/entrypoint.bat"]