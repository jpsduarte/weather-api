# 🌦️ Weather Forecast API (.NET Minimal API)

This project is a **simple and clean .NET Minimal API** that exposes a weather forecast endpoint.  
It was created to demonstrate **modern ASP.NET Core practices**, including minimal APIs, HTTPS, and OpenAPI integration.

---

## 🚀 Technologies

- **.NET 8**
- **ASP.NET Core Minimal APIs**
- **C#**
- **OpenAPI / Swagger**
- **Git / GitHub**

---

## 📌 Features

- 🌤️ Exposes a weather forecast endpoint
- 🔁 Returns a 5-day forecast with random temperature data
- 📄 OpenAPI documentation enabled in development
- 🔐 HTTPS redirection enabled
- 🧱 Clean and minimal project structure

---

## 🌐 Available Endpoint

### `GET /weatherforecast`

Returns an array of weather forecast objects.

### Example response

```json
[
  {
    "date": "2026-01-19",
    "temperatureC": 23,
    "summary": "Mild",
    "temperatureF": 73
  }
]
```

---

## ▶️ Running the project

### Prerequisites

- .NET 8 SDK installed

### Steps

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
dotnet restore
dotnet run
```

The API will be available at:

```text
https://localhost:xxxx/weatherforecast
```

If running in **Development**, OpenAPI will be available at:

```text
https://localhost:xxxx/openapi
```

---

## 🧠 Key Technical Notes

- Uses **Minimal APIs** for reduced boilerplate
- `record` types are used for immutable data models
- OpenAPI is only enabled in Development environment
- HTTPS redirection is enabled by default

---

## 🛠️ Possible Improvements

- 🔗 Replace random data with a real weather provider
- 🧪 Add automated tests
- 🔐 Add authentication and authorization
- 📊 Add logging and observability
- 🚀 Add CI pipeline with GitHub Actions

---

## 📄 License

This project is open-source and intended for learning and demonstration purposes.

---

## 👤 Author

**João Paulo dos Santos Duarte**  
Software Engineer | Product Manager  
🇧🇷 Brazil  
