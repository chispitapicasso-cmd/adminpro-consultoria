# AdminPro — sitio web

Landing page estática para **AdminPro Consultoría Empresarial**, basada en la presentación compartida.

## Archivos

- `index.html` — estructura y contenido de la página.
- `styles.css` — identidad visual azul/orgánica, responsive y componentes.
- `script.js` — menú móvil, animaciones de entrada, año dinámico y validación del formulario.

## Cómo verla

Desde esta carpeta puedes iniciar un servidor local con:

```bash
python3 -m http.server 8080
```

Luego abre `http://localhost:8080` en el navegador.

## Antes de publicar

1. Sustituye en `index.html` los datos de contacto por el correo y/o WhatsApp reales de AdminPro.
2. Conecta el formulario (`#contact-form`) a un servicio de recepción de formularios o a tu backend. Actualmente valida los campos y muestra una confirmación local, pero no envía datos a un servidor.
3. Confirma si los precios iniciales y la promoción de lanzamiento siguen vigentes.
4. Si ya tienes logotipo, redes sociales o fotografías, se pueden integrar en los espacios correspondientes.

La web evita inventar testimonios o resultados y presenta la información del PDF en lenguaje orientado a clientes.
