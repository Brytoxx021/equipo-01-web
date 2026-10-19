# Cómo contribuir a EQUIPO-avsl-WEB

¡Gracias por querer ayudar! Esta guía explica cómo proponer cambios.

## Primeros pasos

1. Haz un fork del repositorio y clónalo en tu equipo.
2. Busca un issue y comenta que quieres trabajar en él, para que nadie más lo duplique.

## Nombres de rama

Usa el formato `tipo/descripcion-corta-en-minusculas`:

| Tipo      | Cuándo usarlo                    | Ejemplo                          |
|-----------|----------------------------------|----------------------------------|
| `feat`    | Nueva funcionalidad              | `feat/filtro-por-categoria`      |
| `fix`     | Corrección de un error           | `fix/boton-contacto-movil`       |
| `docs`    | Cambios en documentación         | `docs/instrucciones-instalacion` |
| `style`   | Formato o estilos sin cambio lógico | `style/espaciado-footer`      |
| `refactor`| Reorganizar código sin cambiar comportamiento | `refactor/separar-estilos` |

## Mensajes de commit

Formato: `tipo: descripción breve en imperativo` (máximo 72 caracteres).

- `feat: añadir filtro por categoría en la galería`
- `fix: corregir el desbordamiento del menú en móvil`
- `docs: explicar cómo ejecutar el proyecto en local`

Un commit debe hacer una sola cosa. Si necesitas escribir "y" en el mensaje, probablemente son dos commits.

## Pull Requests

Antes de abrir tu PR, comprueba que:

- [ ] Parte de una rama con el nombre correcto y está actualizada con `main`.
- [ ] Los commits siguen el formato indicado.
- [ ] Has probado los cambios en local y funcionan.
- [ ] No incluye cambios ajenos al issue.

La descripción de la PR debe incluir:

1. **Qué cambia** y por qué, en 2-3 líneas.
2. **Issue relacionado**, con `Closes #número`.
3. **Cómo probarlo**: pasos para que quien revise lo compruebe.
4. **Capturas de pantalla** si hay cambios visuales.

## Revisión

Una persona del equipo revisará tu PR en un plazo aproximado de 3 días. Puede pedirte cambios: es lo habitual y forma parte del proceso.

## Código de conducta

Sé respetuoso y constructivo. Aquí todas las preguntas son bienvenidas.
