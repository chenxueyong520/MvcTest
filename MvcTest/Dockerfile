FROM microsoft/aspnetcore:2.0
ARG source
WORKDIR /app
EXPOSE 8087
COPY ${source:-obj/Docker/publish} .
ENTRYPOINT ["dotnet", "MvcTest.dll"]
