FROM microsoft/dotnet:2-sdk
WORKDIR /integration

COPY IntegrationTests.csproj .
RUN dotnet restore

COPY . .
ENTRYPOINT [ "dotnet", "test" ]
