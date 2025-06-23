# FTSAPP

## Uso

### 1. Ejecutar el servidor de archivos TLS

```bash
node secure-server.js
```

Este servidor escucha en el puerto **6000** y maneja las operaciones seguras de archivos (LIST, GET, PUT, DELETE, RENAME).

---

### 2. Ejecutar el servidor web HTTPS

En otra terminal:

```bash
node web-server.js
```

Este servidor expone la interfaz web segura en **[https://localhost:3000](https://localhost:3000)** y se comunica internamente con el servidor TLS.

---

### 3. Acceder a la interfaz web

Abrir el navegador y entrar a:

```
https://localhost:3000
```

> Nota: Debés aceptar el certificado autofirmado (generalmente en el navegador te avisará "Sitio no seguro").

---

### 4. Funcionalidades desde la UI

* **Subir archivo:** Seleccioná un archivo y clic en "Subir".
* **Listar archivos:** Se muestran todos los archivos disponibles en el servidor.
* **Descargar archivo:** Clic en "Descargar" para bajar el archivo.
* **Renombrar archivo:** Clic en "Renombrar", ingresar nuevo nombre.
* **Eliminar archivo:** Clic en "Eliminar" y confirmar.

---

