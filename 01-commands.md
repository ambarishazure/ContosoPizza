dotnet new webapi -f net6.0           

dotnet run

https://localhost:{PORT}/weatherforecast  
https://localhost:7129/weatherforecast

dotnet tool install -g Microsoft.dotnet-httprepl         

httprepl https://localhost:{PORT}
httprepl https://localhost:7129

connect https://localhost:7129

ls

cd WeatherForecast

get

exit
