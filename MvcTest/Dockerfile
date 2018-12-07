FROM microsoft/aspnetcore:2.0
ARG source
WORKDIR /app
ENV ASPNETCORE_URLS http://+:8087
EXPOSE 8087
COPY ${source:-obj/Docker/publish} .
ENTRYPOINT ["dotnet", "MvcTest.dll"]
