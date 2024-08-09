# devTalles - Visual Studio Code: Mejora tu velocidad para codificar

Fuente del curso: https://cursos.devtalles.com/courses/take/visual-studio-code/lessons/44761313-mis-recomendaciones-iniciales

# ShortCuts

- [Atajos en Windows](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf)
- [Atajos en Mac OSX](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf)
- [Atajos en Linux](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf)
- [Tips and Tricks - Oficial](https://code.visualstudio.com/docs/getstarted/tips-and-tricks)

## Sección 2: Ediciones y tips básicos

1.  Movimientos de líneas

-        ⌥ ↓ / ⌥ ↑ o Alt + ↑ / ↓
-

2.  Ordernar líneas Asc o Desc

-        Seleccionar las líneas > Crl P >  Sort lines Asc

4.  Comentar un bloque de código

-        ⌘ / o  Ctrl + \
-        ⇧ ⌥ A o
-
-        Ctrl + \
-        Shift + Alt + A

5.  Crear un archivo a partir de un enlace <a href="enlace-aquí"></a>

-        ⌥ click derecho
-        Ctrl + click derecho

* Cerrar un tab

- ⌘ w
- Ctrl + w

* Volver a abrir tab cerrado

- ⌘ ⇧ t
- Ctrl + Shift + t

1.  Ir y ojear definiciones (funciones)

-        Ojear definición   ⌥ F12
-        Ir a la definición F12
-
-        Ojear definición   Alt + F12
-        Ir a la definición F12
-

* Abrir una definición (función o tipo)

- ⌘ + mouse sobre texto (nombre de función o tipo)
- Ctrl + mouse sobre texto

7.  Borrar multilíneas seleccionadas que contienen una misma palabra

-         Seleccionar todas las ocurrencias de la selección
-         ⇧ ⌘ L
  Ctrl + Shift + L

8.  Deshacer y rehacer el código

-         ⌘ Z
-         ⌘ ⇧ Z
-         Ctrl +Z
-         Ctrl + Shift + Z

- Modo Zen (zen mode)
-         ⌘ K (suelta y) Z
-         Ctrl + K (suelta y) Z
-          Ctrl > P > zen mode

10. Ocultar-Mostrar terminal

-        ⌃ `
-        Ctrl + `

11. Utilizar emmet wrap

-        Crear atajo (shortcut) para el mismo
-        ⇧ ⌘ P
-        Ctrl + SHIFT + P
  convertir:  
   node --version
  en esto:

```html
<p>
  <li>
    <ul class="text-center">
      node --version
    </ul>
  </li>
</p>
```

Presionamos nos posicionamos frente a `node --version` y después `⇧ ⌘ P` y después seleccionamos `wrap with abreviation`
y tecleamos: `p>li>ul.text-center`

12. Manejo de tabs: Abrir, reabrir, cerrar tabs, cambiar de tab

-        ⌘ W      Cerrar tab  / Cerrar aplicación
-        ⌘ K ⌘ W  Cerrar todas
-        ⇧ ⌘ T    Reabrir anterior
-        ⌃ TAB    Cambiar de tab
-
-        Ctrl + W            Cerrar tab
-        Ctrl + K  Ctrl + W  Cerrar todas
-        Ctrl + Shift + T    Reabrir anterior
-        Ctrl + TAB          Cambiar de tab

- Buscar un archivo desde el command pallete

-        ⌘ P (poner nombre del archivo a buscar)
-        Ctrl + P

- Tabulaciones (mover selección o línea un tab a la derecha o quitarlo)
-          Tab
-          Tab + Shift

## Sección 3: Multi Cursores y edición rápida

- Clonar líneas

*        ⇧ ⌥ (Arrow Down | Up )
*        Shift + Alt + (Arrow Down | Up)
*

- Revisar shortcuts

*        ⌘ K ⌘ S
*        Ctrl + K Ctrl + S

---

## Terminal

    Ctrl + r Search in the history

## Basic Editing

    Ctrl + x Cut line
    Ctrl + c Copy line
    Alt + Up or Down Move line up / down
    Shift + Alt + Up or Down Copy line up / down
    Ctrl + Shift + k Delete line
    Enter Insert line below
    Ctrl + Shift + Enter Insert line above
    Ctrl + f Find
    Ctrl + h Replace
    Ctrl + / Toggle line comment
    Shift + Alt + a Toggle block comment
    Alt + z Toggle word wrap
    Alt + Mouse click Select multiple line individually
    Tab Ident line
    Shift + tab Ident back the line

## Navigation

    Ctrl + Shift + ` Open new terminal
    Ctrl + Shift + m Open Problem Panel
    Ctrl + P Go to File

## Display

    Ctrl + / - Zoom in / out
    Ctrl + b Show Sidebar visibility
    Ctrl + Shift + f Show search
    Ctrl + Shift + x Show Extension
    Ctrl + Shift + d Show Debug
    Ctrl + Shift + u Show output panel
    Ctrl + Shift + g Show source control
