FROM mcr.microsoft.com/dotnet/sdk:5.0

WORKDIR /app

COPY ./hello.* .

RUN dotnet restore; \
    dotnet publish -c Release -o /app/out

CMD ["dotnet", "/app/out/hello.dll"]
