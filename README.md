# moduloAdmin

## Configuracion con .env

1. Copia el archivo de ejemplo:

```bash
cp .env.example .env
```

2. Completa los valores reales en `.env`.

3. La app carga `.env` desde `src/main/resources/application.properties` con:

```properties
spring.config.import=optional:file:.env[.properties]
```
