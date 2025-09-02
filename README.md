# Dokploy Docker Setup

Este proyecto levanta **Dokploy** en Docker con **Postgres** y **Redis**, listo para pruebas en Linux/Mac.  

---

## Requisitos

- Docker 20+  
- Docker Compose 2+  
- Linux o MacOS (Mac M1/M2 compatible)  

---

## Contenido

- `docker-compose.yml` – Levanta Dokploy, Postgres y Redis con los volúmenes y redes configurados.  

---

## Paso a paso

### 1. Clonar el proyecto o crear carpeta

```bash
cd dockploy-yml
```

```bash
docker compose up -d
```
```bash
http://localhost:3000
```


>[!NOTE]
>Este archivo está pensado para facilitar la ejecución de Dockploy en Mac.
Para más información y documentación oficial, visita el proyecto principal:
https://github.com/dokploy/dokploy

