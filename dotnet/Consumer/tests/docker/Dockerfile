FROM artifact.invicti.com/docker/dotnet/sdk:6.0

WORKDIR /app
COPY . ./
RUN dotnet build
RUN dotnet --info

ENTRYPOINT ["dotnet", "test"]