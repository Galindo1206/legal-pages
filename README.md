# DG Soluciones — Centro Legal

Sitio estático para publicar las políticas de privacidad y los términos y condiciones de los proyectos de software de DG Soluciones.

## Estructura

```text
.
├── index.html
├── assets/
│   └── styles.css
└── skybot/
    ├── privacy.html
    └── terms.html
```

## Vista local

No requiere instalación ni proceso de compilación. Puedes abrir `index.html` directamente en el navegador o servir el repositorio con un servidor HTTP local, por ejemplo:

```powershell
python -m http.server 8000
```

Luego visita `http://localhost:8000/`.

## Publicación en GitHub Pages

1. Revisa y reemplaza todos los textos marcados como `PENDIENTE DE COMPLETAR` en las páginas legales.
2. Solicita una revisión legal del contenido antes de publicarlo.
3. Sube los cambios a la rama que se usará para la publicación.
4. En GitHub, abre **Settings → Pages**.
5. En **Build and deployment**, selecciona **Deploy from a branch**.
6. Selecciona la rama correspondiente (por ejemplo, `main`) y la carpeta `/ (root)`.
7. Guarda la configuración y espera a que GitHub muestre la URL publicada.

Todas las rutas del sitio son relativas y funcionan tanto en un dominio propio como en una ruta de proyecto de GitHub Pages.

## Revisión previa a publicación

- Completar la identidad y los datos de contacto del responsable.
- Confirmar las finalidades, proveedores, transferencias y plazos reales de conservación.
- Confirmar los datos de inscripción de los bancos de datos personales, cuando corresponda.
- Definir los canales operativos para ejercer derechos sobre datos personales y solicitar atención humana.
- Completar la fecha de vigencia y los datos comerciales indicados en los términos.
- Validar la redacción con asesoría legal peruana y con la configuración real de WhatsApp Business Platform.

## Alcance

Este repositorio contiene borradores informativos y no sustituye asesoría legal. No incluye backend, credenciales ni datos personales reales.
