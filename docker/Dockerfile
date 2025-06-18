# Use an official .NET SDK image
FROM mcr.microsoft.com/dotnet/sdk:7.0 AS build

# Set the working directory
WORKDIR /app

# Copy everything and build
COPY . .
RUN dotnet build

# Set entrypoint
ENTRYPOINT ["dotnet", "run"]
