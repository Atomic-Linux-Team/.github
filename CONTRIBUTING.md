<h1 align="center">Guía de Contribución a Atomic Linux 🚀</h1>

> ***Aquí tú eres el dueño de tu código, pero la comunidad es el motor del sistema.***

¡Qué bueno que quieras meterle mano al proyecto! En **Atomic Linux**, no buscamos un ejército de seguidores pasivos; queremos desarrolladores independientes que quieran proponer mejoras, corregir *bugs*, optimizar configuraciones o expandir el ecosistema, siempre bajo el principio de que **lo que tú desarrollas es tuyo**.

---

<h2 align="center">💡 ¿Por qué contribuir?</h2>

* **Soberanía y Reconocimiento:** Cada línea de código, parche o documentación que aportes se queda bajo tu propiedad intelectual, respaldado por nuestras licencias (*MIT, GPL-v3.0 y AGPL-v3.0*). Nosotros te damos el crédito completo ante la comunidad.
* **Romper el Molde:** Estás ayudando a construir una alternativa real frente al software controlado por corporaciones. Tu aporte ayuda a mantener el sistema libre, modular y optimizado.

---

<h2 align="center">⏰ ¿Cuándo hacer una contribución?</h2>

No necesitas ser un desarrollador senior con 20 años de experiencia en el kernel de Linux. Puedes abrir un *Issue* o un *Pull Request* cuando:
1. **Encuentres un Bug:** Si algo se rompe en la ISO, en los scripts de instalación o en las configs de Hyprland/Waybar.
2. **Tengas una Optimización:** Si reestructuraste un script en Bash/ZSH para hacerlo más rápido, o encontraste una mejor forma de gestionar los dotfiles.
3. **Falta de Documentación:** Si ves que un paso en el README no está claro o falta explicar cómo configurar algún apartado del sistema.
4. **Nuevas Características:** Si quieres añadir un módulo o un script útil que mejore la experiencia de uso general (en fase BETA todo aporte suma).

---

<h2 align="center">🛠️ ¿Cómo contribuir? (El Flujo de Trabajo)</h2>

Para mantener el repositorio limpio y evitar conflictos de fusión (*merge conflicts*), seguimos el flujo estándar de Git:

### 1. Detectar o Proponer
Antes de escribir código para cambios grandes, revisa la pestaña de **Issues** o abre una nueva para discutir tu idea. Así nos aseguramos de que nadie esté trabajando en lo mismo al mismo tiempo.

### 2. Hacer el Fork y Clonar
Haz un *Fork* de este repositorio a tu cuenta personal y clónalo en tu máquina local:
```bash
git clone [https://github.com/TU_USUARIO/nombre-del-proyecto.git](https://github.com/TU_USUARIO/nombre-del-proyecto.git)
```
### 3. Buscar la simplicidad segura
también, asegurate de crear una nueva rama (*Branch*) que sea especificamente para tu problema
```bash
git checkout -b feature/mejora-scripts
# o para corregir un error:
git checkout -b fix/error-hyprland
```

### 4. Haz Commits limpios, rapidos y que vallan directo al grano
De esta forma nos aseguramos de que, a la hora de verificar y/o revisar tu *fork* se nos hace mas simple y facil entenderlo
```bash
git checkout -b feature/mejora-scripts
# o para corregir un error:
git checkout -b fix/error-hyprland
```
### 5. Push y Pull Request
Sube tus cambios a tu repositorio remoto:
```bash
git push origin feature/mejora-scripts
```
Luego, ven al repositorio matriz de la organización y abre un Pull Request. Describe detalladamente qué hace tu código y qué problema resuelve.

* Manténlo Estético: Si vas a modificar componentes visuales o herramientas de la terminal (como Kitty, Fastfetch o el shell), asegúrate de mantener la coherencia minimalista y oscura del sistema.

* Sin Telemetría: Cualquier intento de introducir scripts de rastreo, analíticas ocultas o recolección de datos será rechazado de inmediato y de forma permanente.

* Respeta las Licencias: Todo código aportado debe ser compatible con la mezcla de licencias libres de la organización.

y así logramos mantener el orde total en este lugar de caos y libertad <3

> *Guía establecida el 28 de junio de 2026. Diseña con orgullo, compila sin miedo. — Team Atomic Linux*
