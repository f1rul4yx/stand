# Stand Reminder

Recordatorio para alternar entre sentado y de pie durante la jornada laboral. Temporizador con anillo de progreso, notificaciones del navegador, estadísticas de sesión y presets configurables.

## Características

- Temporizador visual con anillo de progreso
- Cambio automático entre fase sentado / de pie
- Notificaciones del navegador (funcionan en segundo plano)
- Presets rápidos: Pomodoro, Equilibrado, Activo, Concentrado
- Sliders para personalizar los tiempos
- Estadísticas: tiempo de pie, tiempo sentado, ciclos completados y ratio

## Uso con Docker

```bash
docker compose up -d
```

La app estará disponible en `http://localhost:3000`.

## Variables de entorno

| Variable | Valor por defecto | Descripción |
|----------|-------------------|-------------|
| `PORT`   | `3000`            | Puerto del servidor |
| `TZ`     | `Europe/Madrid`   | Zona horaria del contenedor |

## Build local

```bash
cd build
npm install
npm start
```
