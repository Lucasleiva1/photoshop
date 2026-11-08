# Skills para Photoshop

Repositorio de instrucciones reutilizables de Codex para editar imágenes en Adobe Photoshop. La primera skill, [`photoshop-retoque-profesional`](.agents/skills/photoshop-retoque-profesional/SKILL.md), se centra en retratos, brillos de luz y correcciones locales. Las próximas skills se pueden agregar como carpetas independientes dentro de `.agents/skills/`.

## Uso

Este repositorio ya ubica la skill en `.agents/skills/`, la carpeta de skills del proyecto para Codex. Abrí esta carpeta como proyecto y pedí, por ejemplo: «Usá la skill `photoshop-retoque-profesional` para quitar los brillos de este retrato en Photoshop». Para reutilizarla en otro proyecto, copiá la carpeta completa `.agents/skills/photoshop-retoque-profesional/` a la misma ubicación dentro del proyecto de destino. Iniciá una sesión nueva de Codex en ese proyecto para que la detecte.

La skill guía el diagnóstico y la edición, pero no modifica una imagen por sí sola. Para un retoque concreto hacen falta la imagen original, acceso a Photoshop y las preferencias de salida. El PSD editable y los archivos exportados se guardan en el proyecto de la imagen, no en este repositorio de instrucciones.

## Criterio editorial

La guía inicial del usuario se revisó junto con documentación oficial de Adobe. La skill conserva los procedimientos útiles y corrige atajos que no funcionan de forma general. No incluye acciones, presets ni LUTs de terceros sin verificar. Las fuentes y las decisiones técnicas están en [`references/criterios.md`](.agents/skills/photoshop-retoque-profesional/references/criterios.md).
