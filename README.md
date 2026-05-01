# 📘 Curso de GitHub — De cero a PRO

> Repositorio gratuito y abierto para aprender Git y GitHub desde absolutamente cero hasta nivel profesional.
> Sin cursos de pago. Sin registros. Solo abre VS Code, abre la terminal y empieza.

🔗 Repositorio en GitHub: [https://github.com/yetsin7/Curso-de-GitHub](https://github.com/yetsin7/Curso-de-GitHub)

## Documentacion de referencia

Consulta [DOCUMENTACION-OFICIAL.md](./DOCUMENTACION-OFICIAL.md) para practicar
este curso acompanado por la referencia oficial de Git y GitHub.

---

## 🇳🇮 Para estudiantes de Nicaragua (y de toda Latinoamérica)

Si estás en Nicaragua y quieres aprender a programar, este libro es para ti.
No importa si vives en Managua, León, Estelí, Matagalpa, Granada, Bluefields o en una comunidad rural sin internet estable. No importa si estudias en una universidad, en un instituto técnico, o si estás aprendiendo por tu cuenta desde tu casa. Si tienes una computadora y ganas de aprender, ya tienes lo necesario para empezar.

Este material también funciona para estudiantes y autodidactas de Honduras, El Salvador, Guatemala, Costa Rica, Panamá, México, Colombia, Venezuela, Perú, Argentina, Chile, y cualquier país donde se hable español. La meta es que el idioma y el costo dejen de ser una barrera para aprender tecnología.

---

## 💡 ¿Por qué existe este libro?

En Nicaragua hay muchísimo talento, pero pocos recursos accesibles para aprender programación de manera seria y ordenada. Los cursos en línea suelen ser caros, muchos están solo en inglés, y casi todos exigen registro, pago o internet permanente.

Este libro nace con una misión clara:

- **Aumentar el número de programadores en Nicaragua.**
- **Democratizar el acceso al conocimiento técnico** en español.
- **Demostrar que se puede aprender sin pagar miles de córdobas** en cursos.
- **Apoyar al estudiante que no tiene internet 24/7** — una vez clonado, este repositorio funciona offline.

Aquí no se pide tarjeta de crédito, ni correo, ni suscripción. Solo se pide algo: que estudies con disciplina y que, si te sirve, lo compartas con otra persona que también quiera aprender.

---

## 🎯 ¿Para quién es esto?

Para **cualquier persona** que quiera aprender a usar Git y GitHub como un profesional.
No necesitas experiencia previa con control de versiones. Solo necesitas:

- ✅ Tener **VS Code** instalado
- ✅ Tener un **navegador web** (Chrome, Firefox, Edge, etc.)
- ✅ Ganas de aprender

Al terminar este libro deberías entender:

- cómo Git guarda historial;
- por qué Git no es lo mismo que GitHub;
- cómo colaborar sin pisar el trabajo de otras personas;
- cómo viajan los cambios entre tu computadora y la nube;
- cómo funciona un flujo profesional con ramas, PRs y automatización.

---

## ✅ ¿Qué hace especial a este recurso?

- **100 % gratuito.** Nadie te va a cobrar nada, nunca.
- **Sin registro.** No necesitas crear cuenta en ninguna plataforma para usar este libro.
- **Funciona offline.** Una vez que clones el repositorio en tu computadora, puedes estudiar sin internet.
- **En español claro y natural**, pensado para que cualquier persona lo entienda.
- **Comentado paso a paso**, para que aprendas el porqué de cada comando, no solo a copiarlo.

---

## 🚀 ¿Cómo usar este repositorio?

1. Descarga o clona este repositorio en tu computadora
2. Ábrelo con VS Code (`Archivo → Abrir Carpeta`)
3. Ve a la carpeta `01-introduccion-git` y abre el archivo `README.md`
4. Lee la explicación y luego abre los archivos `.sh` en orden
5. **Lee cada línea** — todo está comentado para que entiendas el porqué
6. Ejecuta los comandos en tu terminal uno por uno (no ejecutes el archivo completo)

> **Tip:** Los archivos `.sh` están pensados para leerse primero y ejecutarse
> línea por línea. La idea es entender el efecto de cada comando.

## 🧠 Qué pasa realmente cuando usas Git

Git no "sube archivos mágicos". Git crea una base de datos local en la carpeta
oculta `.git` donde guarda objetos, historial, referencias y cambios. GitHub, en
cambio, aloja repositorios remotos y herramientas de colaboración sobre ese
historial.

Cuando haces `git add`, `git commit`, `git push` o `git pull`, estás moviendo y
registrando información de formas distintas. Entender eso te hace mucho más
seguro usando Git.

---

## 🛠️ Instalar Git (si aún no lo tienes)

### Windows
1. Ve a [https://git-scm.com/downloads](https://git-scm.com/downloads)
2. Descarga el instalador para Windows
3. Ejecuta el instalador (las opciones por defecto están bien)
4. Al terminar, abre una terminal y escribe `git --version`

### macOS
```
brew install git
```
O descárgalo desde [https://git-scm.com/downloads](https://git-scm.com/downloads)

### Linux (Ubuntu/Debian)
```
sudo apt update && sudo apt install git
```

Verifica la instalación:
```
git --version
```
Si ves algo como `git version 2.x.x`, estás listo.

---

## 📚 Estructura del libro

### 🟢 Nivel Básico — Primeros pasos con Git y GitHub

| Carpeta | Tema |
|---|---|
| `01-introduccion-git/` | ¿Qué es Git? ¿Qué es GitHub? Conceptos fundamentales |
| `02-instalacion-y-configuracion/` | Instalar Git y configurarlo correctamente |
| `03-crear-cuenta-github/` | Crear tu cuenta en GitHub y configurar tu perfil |
| `04-repositorios-basicos/` | Crear, clonar y entender repositorios |
| `05-flujo-basico-git/` | add, commit, push, pull — el flujo diario de trabajo |
| `06-ramas/` | Crear, cambiar y fusionar ramas |
| `07-repositorios-remotos/` | Conectar repositorios locales con GitHub |
| `08-github-interfaz/` | Navegar y usar la interfaz web de GitHub |

### 🟡 Nivel Medio — Trabajo colaborativo

| Carpeta | Tema |
|---|---|
| `09-markdown/` | Escribir documentación con Markdown |
| `10-gitignore/` | Ignorar archivos que no deben subirse |
| `11-pull-requests/` | Proponer cambios y revisión de código |
| `12-issues-y-proyectos/` | Reportar bugs, organizar tareas y proyectos |
| `13-conflictos/` | Resolver conflictos de merge como un profesional |
| `14-git-avanzado/` | Rebase, stash, cherry-pick, reflog y más |
| `15-github-actions/` | Automatización con CI/CD |

### 🔴 Nivel Avanzado — Uso profesional

| Carpeta | Tema |
|---|---|
| `16-github-pages/` | Publicar sitios web gratis con GitHub Pages |
| `17-colaboracion-open-source/` | Contribuir a proyectos de código abierto |
| `18-estrategias-de-ramas/` | Git Flow, GitHub Flow, Trunk-Based Development |
| `19-seguridad/` | Firmar commits, tokens, secretos y buenas prácticas |
| `20-github-cli/` | Usar GitHub desde la terminal con `gh` |
| `21-tips-y-trucos/` | Trucos profesionales para el día a día |
| `22-proyecto-final/` | 🎯 Proyecto integrador: colaboración completa |

---

## 🎓 Consejos para aprender bien

- **No copies y pegues.** Escribe los comandos tú mismo, aunque sea lento al principio.
- **Ejecuta cada comando** y observa qué pasa en tu terminal.
- **Experimenta** — crea repos de prueba, rompe cosas a propósito, aprende del error.
- **Si no entiendes algo, busca en Google o pregunta a una IA** — eso es normal y válido.
- **No saltes capítulos** — cada uno construye sobre el anterior.

---

## 🤝 Cómo apoyar este proyecto

Este libro es gratuito y siempre lo será. Si te ha sido útil, hay maneras sencillas de ayudar a que llegue a más personas en Nicaragua y el resto de Latinoamérica:

- ⭐ **Dale una estrella al repositorio** en GitHub. Cada estrella ayuda a que más estudiantes lo encuentren.
- 📣 **Compártelo** con amigos, compañeros de clase, profesores o cualquier persona que quiera aprender a programar.
- 🐛 **Abre un issue** si encuentras un error, una explicación confusa o algo que se puede mejorar.
- 🔧 **Envía un pull request** si quieres aportar correcciones, mejoras, ejemplos o nuevos temas.
- 💬 **Recomienda este recurso** en tu universidad, instituto, bootcamp o comunidad técnica.

Repositorio: [https://github.com/yetsin7/Curso-de-GitHub](https://github.com/yetsin7/Curso-de-GitHub)

---

## 📄 Licencia

Este proyecto es **completamente gratuito y libre**.
Puedes usarlo, compartirlo, modificarlo y distribuirlo sin restricciones.

---

*Hecho con ❤️ desde Nicaragua, para que cualquier persona pueda aprender Git y GitHub.*
