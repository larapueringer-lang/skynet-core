# SkynetHealthApi

Eine einfache .NET 8 Web API mit einem `/health` Endpoint.

## Voraussetzungen

- [.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)

## Starten

```bash
cd SkynetHealthApi
dotnet run
```

Die API läuft dann auf `http://localhost:5000`.

## Endpoints

### GET /health

Gibt den aktuellen Status der API zurück.

**Response (200 OK):**

```json
{
  "status": "healthy",
  "timestamp": "2026-04-03T20:00:00Z"
}
```

## Beispiel

```bash
curl http://localhost:5000/health
```
