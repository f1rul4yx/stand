# stand

Recordatorio para alternar entre sentado y de pie durante la jornada laboral.

## Qué es

Temporizador web con anillo de progreso que alterna entre fases de sentado y de pie. Incluye notificaciones del navegador, presets rápidos (Pomodoro, Equilibrado, Activo, Concentrado) y estadísticas de sesión.

## Instalación

```bash
git clone https://github.com/f1rul4yx/stand.git
cd stand
```

Variables de entorno opcionales en `docker-compose.yml`:

| Variable | Por defecto | Descripción |
|---|---|---|
| `PORT` | `3000` | Puerto del servidor |
| `TZ` | `Europe/Madrid` | Zona horaria |

## Uso

```bash
docker compose up -d
```

Accede a `http://localhost:3000`.

```bash
docker compose down       # Parar
docker compose restart    # Reiniciar
docker compose logs -f    # Ver logs
```

## Build

```bash
docker build -t f1rul4yx/stand:latest ./build
docker push f1rul4yx/stand:latest
```
