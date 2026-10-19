# Presentación Interactiva: Práctica DML/TCL en PostgreSQL

Presentación interactiva tipo diapositiva (estilo PowerPoint/Keynote para desarrolladores) desarrollada con tecnologías web estándar (**HTML5**, **Vanilla CSS3** y **Vanilla JavaScript**) sin dependencias ni compiladores requeridos.

---

## 🚀 Cómo Ejecutar la Presentación

1. **Abrir directamente:** Haz doble clic en [`index.html`](file:///d:/TBD4/index.html) para abrirla en cualquier navegador moderno (Google Chrome, Microsoft Edge, Mozilla Firefox, Brave, Safari).
2. **Servidor local (opcional):**
   ```bash
   python -m http.server 8080
   ```
   Luego visita `http://localhost:8080`.

---

## ⌨️ Controles y Atajos de Teclado

| Tecla / Acción | Función |
| :--- | :--- |
| **`→` / `Espacio` / `AvPág`** | Avanzar a la siguiente diapositiva |
| **`←` / `RePág`** | Retroceder a la diapositiva anterior |
| **`Inicio` / `Fin`** | Ir a la primera / última diapositiva |
| **`T`** | Alternar entre **Modo Oscuro** y **Modo Claro** |
| **`M`** | Abrir la **Cuadrícula / Resumen** de las 15 diapositivas |
| **`F`** | Activar / desactivar modo **Pantalla Completa** |
| **`H` / `?`** | Mostrar el modal de atajos de teclado |
| **`Escape`** | Cerrar cualquier ventana modal activa |

---

## 🎨 Características UI/UX Implementadas

1. **Estética Developer Tech Premium:**
   - Efectos **Glassmorphism** (`backdrop-filter: blur(16px)`).
   - Paleta de colores inspirada en **PostgreSQL** (`#336791`, acentos cian neón `#38bdf8`, verde esmeralda `#10b981` y fucsia transaccional `#ec4899`).
   - Tipografía moderna desde Google Fonts: *Outfit*, *Inter*, *JetBrains Mono* y *Fira Code*.

2. **Bloques de Código SQL Estilo Terminal / IDE:**
   - Barra superior con controles estilo macOS (botones rojo, amarillo y verde).
   - Resaltado de sintaxis SQL completo (palabras clave, comandos TCL, funciones agregadas, tipos de datos, comentarios y cadenas).
   - Botón interactivo **"Copiar"** con retroalimentación visual al portapapeles.

3. **Espacios Interactivos para Capturas de pgAdmin 4:**
   - Contenedores estilizados con bordes punteados e íconos.
   - Botón **"Insertar Captura"** (`<input type="file">`): Permite cargar directamente las capturas de pantalla de pgAdmin 4 desde la computadora y visualizarlas inmediatamente.
   - Botón **"Ver Resultado Simulado"**: Permite desplegar una réplica exacta de la tabla o árbol de pgAdmin 4 con los datos exactos del informe académico.

4. **15 Diapositivas Estructuradas:**
   - **Slide 01:** Portada (UPDS, Facultad de Ingeniería, Autores, Docente, Fecha).
   - **Slide 02:** Introducción y Objetivos (General y Específicos).
   - **Slide 03:** Conceptos Clave (DML vs TCL en tarjetas interactivas).
   - **Slide 04:** Creación de Tablas (DDL relacional y constraints).
   - **Slide 05:** Carga Inicial de Datos (Poblado inicial y SELECTs).
   - **Slide 06:** Ejercicio 1 - Venta Atómica con COMMIT (CTE + RETURNING).
   - **Slide 07:** Ejercicio 2 - Aumento con Subconsulta NOT IN (+10%).
   - **Slide 08:** Ejercicio 3 - Simulación de Error y ROLLBACK (Restauración del monitor).
   - **Slide 09:** Ejercicio 4 - Puntos de Control con SAVEPOINT.
   - **Slide 10:** Ejercicio 5 - Subconsultas de Análisis (AVG y EXISTS).
   - **Slide 11:** Ejercicio 6 - Eliminación Controlada con NOT EXISTS.
   - **Slide 12:** Ejercicio 7 - Transacción Segura Atómica para Descontar Stock.
   - **Slide 13:** Comprobación Final y Auditoría de Ventas/Inventario.
   - **Slide 14:** Recomendaciones Técnicas y Conclusiones.
   - **Slide 15:** Referencias Bibliográficas en formato APA 7ma Edición.
