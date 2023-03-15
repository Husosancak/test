FROM mcr.microsoft.com/dotnet/aspnet:5.0

WORKDIR /app
COPY /bin/Release/net5.0/publish .
ENTRYPOINT ["dotnet", "text.dll"]
#EXPOSE 80
#
#FROM mcr.microsoft.com/dotnet/sdk:5.0 AS build
#WORKDIR /src
#COPY ["text/text.csproj", "text/"]
#RUN dotnet restore "text/text.csproj"
#COPY . .
#WORKDIR "/src/text"
#RUN dotnet build "text.csproj" -c Release -o /app/build
#
#FROM build AS publish
#RUN dotnet publish "text.csproj" -c Release -o /app/publish
#
#FROM base AS final
#WORKDIR /app
#COPY --from=publish /app/publish .
