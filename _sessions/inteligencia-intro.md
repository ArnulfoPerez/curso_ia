---
title: ¿Qué es la Inteligencia Artificial? (Sesión 1)
slug: intro # Este 'slug' se usa para la parte final de la URL (ej. /inteligencia/intro/)
block_slug: inteligencia # ¡Importante! Coincide con el 'slug' del bloque padre
session_order: 1 # Para ordenar las sesiones dentro del bloque
has_notes: true        # Habilita el enlace a notas
has_activity: true     # Habilita el enlace a la actividad
has_presentation: true # Habilita el enlace a la presentación
---

{{ site.session_metadata.inteligencia.intro.description }}

### Objetivos de la Sesión:
<ul>
{% assign session_meta = site.session_metadata[page.block_slug][page.slug] %}
{% if session_meta.obj %}
    {% for obj in session_meta.obj %}
        <li>{{ obj }}</li>
    {% endfor %}
{% endif %}
</ul>

## Contenido de la Sesión
hola mundo
