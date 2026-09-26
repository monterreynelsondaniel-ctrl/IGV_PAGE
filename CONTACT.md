# Contacto — IGEV_SC

Para consultas, inscripciones y dudas generales utiliza los siguientes canales:

- Dirección: San Cristóbal, Estado Táchira, Venezuela
- Correo: info@igev_sc.edu.ve (placeholder)
- WhatsApp: +58 4XX-XXX-XXXX (placeholder)
- Instagram: @igev_sc (placeholder)

## Formulario de contacto (sugerido)
Campos recomendados para el formulario de la web:
- Nombre completo
- Correo electrónico
- Teléfono / WhatsApp
- Curso de interés
- Comentarios / mensajes

### Nota sobre pagos
No se procesan pagos en línea desde la web. La coordinación de matrícula y pagos se realiza en sede o por los canales administrativos indicados en `CONTACT.md`.

Para integrarlo en el sitio, puedes usar un formulario HTML que envíe a un correo o a un servicio de gestión de formularios (Formspree, Netlify Forms, etc.).

Ejemplo de snippet HTML para formulario:

```html
<form action="https://formspree.io/f/xxxxxx" method="POST">
  <input name="name" placeholder="Nombre completo" required />
  <input name="email" type="email" placeholder="Correo" required />
  <input name="phone" placeholder="Teléfono/WhatsApp" />
  <select name="course">
    <option>Cocina Asiática Profesional</option>
    <option>Repostería Profesional</option>
    <option>Coctelería Profesional</option>
  </select>
  <textarea name="message" placeholder="Mensaje"></textarea>
  <button type="submit">Enviar</button>
</form>
```

Sustituye el `action` por tu endpoint o proveedor elegido.