# Cómo usar esta plantilla

Esta guía explica cómo convertir esta plantilla en tu propio perfil de GitHub. Cuando
termines, **puedes borrar este archivo** (`TEMPLATE-USAGE.md`).

## 1. Qué es

Una plantilla del `README.md` que se muestra en tu perfil de GitHub. El truco: GitHub
muestra el README de un repositorio **especial** que tiene el mismo nombre que tu usuario.

## 2. Crear tu perfil

**Opción A — "Use this template" (recomendada):**

1. Pulsa **"Use this template" → Create a new repository**.
2. Nombra el repositorio **exactamente igual que tu usuario de GitHub**
   (ej. si tu usuario es `tuusuario`, el repo debe ser `tuusuario/tuusuario`).
3. Márcalo como **público** y créalo. GitHub mostrará el README en tu perfil automáticamente.

**Opción B — Manual:**

```bash
git clone https://github.com/brayandiazc/github-profile-template-es.git tuusuario
cd tuusuario
rm -rf .git
git init
# crea el repo tuusuario/tuusuario en GitHub y haz push
```

## 3. Personalizar el README

1. Reemplaza los textos marcados con **✏️** y los que van entre `[corchetes]` por tu información.
2. Sustituye **todos** los placeholders por tus datos:
   - `[Tu Nombre]`, tu rol, `tuusuario`, `tuemail@ejemplo.com`, `tusitio.dev`, enlaces de proyectos.
3. En **Proyectos actuales** y **Experiencia**, añade tus entradas (o elimina "Experiencia" si no aplica).
4. En **Stack Tecnológico**, deja solo las categorías y tecnologías que uses; añade las que falten.
5. En **Encuéntrame**, deja solo los badges de las redes que uses y apunta los enlaces a tus perfiles.
   Los badges usan `style=flat`; puedes cambiar `logo` y colores en [shields.io](https://shields.io).
6. En **Contacto**, actualiza tu email y enlaces.
7. Borra el **comentario de instrucciones** del inicio del README y este archivo.

## 4. Verifica antes de publicar

- Que el README **renderice bien** en GitHub (sin Markdown roto).
- Que **no queden placeholders** sin reemplazar.
- Que los badges e imágenes de estadísticas **carguen** correctamente.

¡Listo! Tu perfil ya está activo. 🎉
