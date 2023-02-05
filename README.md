# back-end-net-core
Back-End with ASP.Net Core 6 WebApi to Front-End in Angular & SQL Server

#### ocelot.json
```json
"GlobalConfiguration": {
    "BaseUrl": "https://localhost:5000"
},
```

#### User Service
- **GET** - /gateway/user -> /api/user -> https -> localhost -> 5001 
- **GET** - /gateway/user/{id} -> /api/user/{id} -> https -> localhost -> 5001
- **POST** / PUT - /gateway/user -> /api/user -> https -> localhost -> 5001

#### Product Service
- **GET** - /gateway/product -> /api/product -> https -> localhost -> 5002 
- **GET** - /gateway/product/{id} -> /api/product/{id} -> https -> localhost -> 5002
- **POST** / PUT - /gateway/product -> /api/product -> https -> localhost -> 5002 

#### appsettings.json
```json
"ConnectionStrings": {
    "DefaultConnection": "Data Source=DESKTOP-89IV9FC;Initial Catalog=OcelotGatewayDemo;User Id=sa;Password=xxxxxx;"
}
```

