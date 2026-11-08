---
name: photoshop-retoque-profesional
description: Retocar fotografías y retratos en Adobe Photoshop, especialmente brillos especulares, luces quemadas, halos y problemas locales de piel, luz o color. Usar al editar una imagen real; no para instalar Photoshop ni para crear imágenes nuevas.
---

# Retoque profesional en Photoshop

Trabajá sobre la imagen real del usuario en Photoshop y entregá un resultado natural, editable y comprobado. Priorizá conservar identidad, rasgos, textura de piel y dirección de la luz. Antes de tocar la imagen, acordá solo lo que falte para una decisión material: archivo de entrada, uso final o intensidad deseada del retoque. Si el usuario no especifica estilo, optá por corrección sutil.

## Preparar la sesión

- Confirmá el archivo de entrada y distinguí la foto original de versiones previas. Guardá una copia editable antes de modificar píxeles. No sobrescribas el original.
- Si vas a abrir o controlar la aplicación nativa de Windows, leé `C:\Users\jaell\.codex\DESKTOP_APP_RUNBOOK.md` y la skill de control de Windows disponible en esa sesión. Usá las herramientas de interfaz disponibles, observá el documento y la capa activos después de cada acción importante, y comprobá visualmente el resultado. No des por ejecutado un paso solo porque se envió un atajo.
- Inspeccioná la imagen completa y al 100 %. Ubicá el brillo, su tamaño y bordes; verificá si hay textura recuperable, canales recortados, dominante de color, halo o rasgos faciales tapados. Usá histograma y aviso de recorte cuando ayuden. Separá el problema de reflejos de vidrio, destellos de lente y piel brillante: requieren tratamientos distintos.

## Elegir el tratamiento

1. **Brillo con detalle visible:** comenzá por un ajuste local reversible. En Camera Raw, una máscara con Iluminaciones/Blancos puede reducir la intensidad; en Photoshop, una capa de Curvas con máscara suave permite ajustar forma y transición. Mové los controles hasta conservar volumen y tono de piel. Corregí color en una capa separada si persiste una dominante.
2. **Pequeños puntos especulares:** usá Pincel corrector o Tampón de clonar en una capa vacía de retoque, muestreando una zona cercana con textura, perspectiva e iluminación parecidas. Configurá el muestreo de capas de acuerdo con el documento. Trabajá con trazos cortos, remuestreá a menudo y revisá patrones repetidos. Cerca de bordes, pestañas o cabello, preferí clonado controlado y máscara.
3. **Brillo amplio o transición irregular:** equilibrá primero la luz con Curvas enmascaradas y, si hace falta, igualá pequeñas diferencias de luminosidad con dodge and burn reversible mediante capas de Curvas y máscaras. Usá Parche o clonado solo donde haya una fuente plausible. No alises toda la piel para ocultar el problema.
4. **Área recortada a blanco sin textura:** no prometas recuperar detalle inexistente. Podés reconstruir una zona pequeña desde piel o material comparable, con cuidado de la anatomía y la dirección de luz. Si el brillo tapa ojos, boca u otro rasgo único, detené la reconstrucción especulativa y explicá el límite; pedí otra toma o una referencia si existe.
5. **Halo de lente o velo luminoso:** tratá contraste y color de forma localizada antes de clonar. Dehaze puede ayudar con un velo amplio, pero vigilá saturación, ruido y bordes. Un reflejo de vidrio que cubre gran parte de la imagen es otro caso: evaluá la función de eliminación de reflejos de Photoshop solo si corresponde a ese tipo de reflejo.

No apliques una receta automática a toda la imagen. La separación de frecuencias puede servir para desigualdades extensas de color y textura, pero solo cuando el retoque local más simple no alcance; controlá que no genere piel plástica. Los modos Oscurecer o Multiplicar requieren contenido diferente en la capa superior: una copia idéntica en Oscurecer no elimina brillos y Multiplicar puede oscurecer la imagen entera. No uses acciones, LUTs o presets descargados sin revisar su origen, compatibilidad y efecto.

## Verificar y entregar

- Alterná el antes y después a pantalla completa, 100 % y una ampliación mayor. Buscá halos, manchas grises, piel sin poros, texturas duplicadas, cambios de identidad y contrastes incoherentes. Compará cara, cuello y entorno para mantener continuidad de luz.
- Conservá capas de ajuste, máscaras y retoques con nombres comprensibles en un PSD editable. Exportá una copia adecuada al uso final cuando el usuario la pida. Seguí la convención de nombres versionados del proyecto para archivos destinados a entrega.
- Informá qué se corrigió, qué áreas no tenían detalle real recuperable, dónde están los archivos y qué comprobaste en Photoshop. No afirmes una inspección visual que no realizaste.

Para la justificación técnica, excepciones y enlaces oficiales, consultá [references/criterios.md](references/criterios.md) cuando necesites elegir entre técnicas o explicar un límite.
