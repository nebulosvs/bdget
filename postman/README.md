# Postman - BDGET Semana 3

## Archivos

| Archivo | Tipo |
|---------|------|
| `BDGET-Semana3.postman_collection.json` | Colección |
| `BDGET-Local.postman_environment.json` | Environment (local) |
| `BDGET-AWS-EC2.postman_environment.json` | Environment (EC2) |

## Importar

Postman → **Import** → selecciona los archivos JSON.

## Demo para el video (orden sugerido)

1. **Crear guía (EFS temporal)** — guarda `guiaId` automáticamente
2. **Consultar historial** — por transportista y fecha
3. **Descargar guía** — con transportista válido
4. **Descargar guía (permiso denegado)** — muestra el 403
5. **Subir guía a S3**
6. **Descargar guía** — ahora desde S3
7. **Modificar / actualizar guía**
8. **Eliminar guía** — al final de la demo

## Environments

- **Local:** `http://localhost:8080` (con `mvn spring-boot:run` o `docker compose up`)
- **AWS EC2:** reemplaza `TU_IP_EC2` por la IP pública de tu instancia
