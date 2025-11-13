# Devolución - Examen Recuperatorio
## Control de Versiones con Git y GitHub

**Alumno:** Massimo Sahonero  
**Repositorio:** https://github.com/massi7209/recuperatorio-git-massimo-sahonero  
**Fecha de evaluación:** 13/11/2025

---

## Evaluación por Criterios

### 1. Creación del repositorio remoto - **1/1 pts**
✅ **Cumplido**
- El repositorio fue creado correctamente con el nombre `recuperatorio-git-massimo-sahonero`
- Se incluye el archivo README.md inicial (confirmado por el commit "Initial commit")
- La configuración remota apunta correctamente a GitHub

**Observaciones:** Perfecto. El repositorio fue creado correctamente con la nomenclatura solicitada.

---

### 2. Clonación y primera modificación - **1.5/2 pts**
⚠️ **Parcialmente cumplido**
- ✅ El repositorio fue clonado correctamente
- ✅ Se realizó modificación del README.md en el commit "Update README.md"
- ✅ La información del README incluye correctamente:
  - Título: "# Proyecto de recuperatorio"
  - Descripción del repositorio
  - Materia: Electrónica digital 4
  - Tema: Control de Versiones
  - Año: 2025
- ⚠️ El mensaje del commit fue "Update README.md" en lugar de "Actualizar información del proyecto" como se especificaba en las consignas

**Observaciones:** El contenido es correcto, pero el mensaje del commit no coincide exactamente con lo solicitado en el examen.

---

### 3. Creación de archivo de código - **2.5/3 pts**
⚠️ **Parcialmente cumplido**
- ✅ Se creó la rama `feature-codigo` correctamente
- ✅ Se creó el archivo `programa.py` con la función `saludar()` inicial
- ⚠️ El commit fue "Create programa.py" en lugar de "Agregar archivo programa.py" como se solicitaba
- ✅ Se creó el Pull Request #1 que fue fusionado exitosamente a main

**Observaciones:** Bien ejecutado en términos de flujo de trabajo, pero el mensaje del commit no es el especificado en las consignas.

---

### 4. Sincronización y creación de ramas - **2/2 pts**
✅ **Cumplido**
- Se actualizó la rama main local
- Se crearon las ramas `documentacion` y `actualizacion-codigo` (evidenciado por los PRs posteriores)
- El flujo de trabajo demuestra sincronización correcta

**Observaciones:** Correcto. Las ramas fueron creadas y utilizadas según lo solicitado.

---

### 5. Modificación en rama documentación - **1.5/2 pts**
⚠️ **Parcialmente cumplido**
- ✅ Se modificó el README.md agregando la sección de documentación
- ✅ Se incluyeron los requisitos (Python 3.x, Git instalado)
- ✅ Se agregó la información del autor:
  - Nombre: Massimo Sahonero
  - Fecha: 6/11/25
- ⚠️ Los commits fueron "Update README.md" (múltiples) en lugar de "Agregar sección de documentación"
- ✅ Se creó el Pull Request #2 desde la rama documentacion

**Observaciones:** La documentación fue agregada correctamente, pero el mensaje del commit no coincide exactamente con lo solicitado.

---

### 6. Modificación en rama actualizacion-codigo - **1.5/2 pts**
⚠️ **Parcialmente cumplido**
- ✅ Se modificó el archivo `programa.py` agregando la función `despedir()`
- ✅ Se modificó el README.md cambiando el título a "# Proyecto de recuperatorio - Versión actualizada"
- ⚠️ El commit fue "UPDATE programa.py y README.md" en lugar de "Actualizar programa y README" (mayúsculas innecesarias)
- ✅ Se creó el Pull Request #3 desde actualizacion-codigo

**Observaciones:** Bien ejecutado, aunque el mensaje del commit tiene diferencias con el solicitado (uso de mayúsculas y "UPDATE" en lugar de "Actualizar").

---

### 7. Generación y resolución del conflicto - **3/4 pts**
⚠️ **Parcialmente cumplido**
- ✅ Se generó el conflicto esperado en el archivo README.md entre las ramas documentacion y actualizacion-codigo
- ✅ El conflicto fue resuelto (evidenciado por el merge exitoso de ambos PRs)
- ✅ Ambos Pull Requests (#2 y #3) fueron fusionados
- ✅ El README.md final incluye:
  - El título actualizado: "# Proyecto de recuperatorio - Versión actualizada"
  - La información original del proyecto (Materia, Tema, Año)
  - La sección de Documentación con requisitos y autor
- ⚠️ **PROBLEMA en programa.py**: El archivo tiene un error de sintaxis/estructura:
  - Hay **DOS bloques `if __name__ == "__main__":`** separados
  - La función `despedir()` está mal indentada (fuera del primer bloque)
  - Esto indica que el merge no fue completamente limpio o hubo un error en la fusión

**Observaciones:** El conflicto en README.md fue resuelto correctamente, pero el archivo programa.py muestra problemas estructurales que sugieren una fusión defectuosa o edición manual incorrecta.

---

### 8. Creación de rama hotfix - **1.5/2 pts**
⚠️ **Parcialmente cumplido**
- ✅ Se creó la rama `hotfix-typo` correctamente
- ✅ Se modificó el mensaje de la función `saludar()` al texto correcto: "¡Bienvenido al sistema de control de versiones!"
- ⚠️ El commit fue "Update programa.py" en lugar de "Corregir mensaje de bienvenida"
- ✅ Se creó y fusionó el Pull Request #4

**Observaciones:** El hotfix fue implementado correctamente en términos de funcionalidad, pero el mensaje del commit no es el especificado.

---

### 9. Sincronización final y limpieza - **0/2 pts**
❌ **NO Cumplido**
- ⚠️ La rama main local está actualizada
- ❌ Las ramas locales NO fueron eliminadas (todavía existen en el repositorio remoto)
- ✅ El repositorio está sincronizado con GitHub

**Observaciones:** Las ramas remotas no fueron eliminadas. Las ramas `feature-codigo`, `documentacion`, `actualizacion-codigo` y `hotfix-typo` aún están en origin. Según las consignas, se debían eliminar las ramas locales después de ser fusionadas.

---

## Resumen de Calificación

| Criterio | Puntaje Obtenido | Puntaje Máximo |
|----------|------------------|----------------|
| 1. Creación del repositorio remoto | 1.0 | 1 |
| 2. Clonación y primera modificación | 1.5 | 2 |
| 3. Creación de archivo de código | 2.5 | 3 |
| 4. Sincronización y creación de ramas | 2.0 | 2 |
| 5. Modificación en rama documentación | 1.5 | 2 |
| 6. Modificación en rama actualizacion-codigo | 1.5 | 2 |
| 7. Generación y resolución del conflicto | 3.0 | 4 |
| 8. Creación de rama hotfix | 1.5 | 2 |
| 9. Sincronización final y limpieza | 0.0 | 2 |

**CALIFICACIÓN FINAL: 14.5/20 puntos**

---

## Comentarios Generales

El alumno demostró un **buen manejo general de Git y GitHub**, completando todas las etapas del examen con un flujo de trabajo correcto. Sin embargo, presenta algunas áreas de mejora importantes.

**Fortalezas:**
- ✅ Comprensión del flujo de trabajo básico con ramas
- ✅ Creación y manejo apropiado de Pull Requests (4 PRs creados y fusionados)
- ✅ Sincronización correcta entre repositorio local y remoto
- ✅ Resolución del conflicto en README.md
- ✅ Todos los archivos contienen las secciones y funciones esperadas
- ✅ Estructura general del trabajo correcta

**Áreas de mejora:**

1. **Mensajes de commits (múltiples etapas - 2.5 pts perdidos):**
   - Los mensajes de commit no coinciden exactamente con los especificados en las consignas
   - Es importante seguir las especificaciones exactas en un examen
   - Ejemplos:
     - "Update README.md" vs "Actualizar información del proyecto"
     - "Create programa.py" vs "Agregar archivo programa.py"
     - "UPDATE programa.py y README.md" vs "Actualizar programa y README"
     - "Update programa.py" vs "Corregir mensaje de bienvenida"

2. **Etapa 7 - Estructura del programa.py (1 pt perdido):**
   - **PROBLEMA ESTRUCTURAL**: El archivo `programa.py` tiene dos bloques `if __name__ == "__main__":` separados
   - La función `despedir()` está mal indentada
   - Esto sugiere un error en el merge o edición manual incorrecta
   - El código debería tener una estructura limpia con un solo bloque principal

3. **Etapa 9 - Limpieza de ramas (2 pts perdidos):**
   - **NO se eliminaron las ramas** locales ni remotas
   - Las ramas `feature-codigo`, `documentacion`, `actualizacion-codigo` y `hotfix-typo` aún existen en origin
   - Esta es una etapa importante para mantener el repositorio limpio

**Análisis del problema en programa.py:**

El archivo actual tiene esta estructura incorrecta:
```python
def saludar():
    print("¡Bienvenido al sistema de control de versiones!")

if __name__ == "__main__":
    saludar()
    
def despedir():
    print("Hasta pronto!")

if __name__ == "__main__":
    saludar()
    despedir()
```

Debería ser:
```python
def saludar():
    print("¡Bienvenido al sistema de control de versiones!")

def despedir():
    print("Hasta pronto!")

if __name__ == "__main__":
    saludar()
    despedir()
```

Este error estructural indica que hubo problemas durante el merge o edición manual después del merge.

**Recomendaciones:**
1. Seguir exactamente los mensajes de commit especificados en las consignas
2. Verificar la estructura y sintaxis del código después de cada merge
3. Probar que el código funciona correctamente antes de finalizar el merge
4. Completar la limpieza de ramas eliminándolas tanto local como remotamente:
   ```bash
   git branch -d feature-codigo documentacion actualizacion-codigo hotfix-typo
   git push origin --delete feature-codigo documentacion actualizacion-codigo hotfix-typo
   ```
5. Revisar el contenido de los archivos después de resolver conflictos

---

## Conclusión

El trabajo demuestra **comprensión sólida de los fundamentos de Git y GitHub**, con un flujo de trabajo generalmente correcto. El alumno completó todas las etapas y demostró capacidad para trabajar con ramas, pull requests y resolución de conflictos.

Los puntos perdidos se deben principalmente a:
- Falta de atención a los detalles específicos (mensajes de commit exactos)
- Error estructural en el archivo programa.py después del merge
- No completar la limpieza final de ramas

**Estado: APROBADO (14.5/20)**

El alumno ha demostrado competencia en el manejo de Git y GitHub. Se recomienda:
1. Prestar más atención a las especificaciones exactas de las consignas
2. Verificar la estructura y funcionamiento del código después de merges
3. Completar todos los pasos incluyendo la limpieza final

Con estas mejoras, el alumno podrá alcanzar calificaciones más altas en futuros trabajos.

---

## Detalle de Archivos Finales

**README.md:**
- ✅ Título "# Proyecto de recuperatorio - Versión actualizada" presente
- ✅ Información del proyecto completa (Materia, Tema, Año)
- ✅ Sección de Documentación presente
- ✅ Requisitos listados correctamente
- ✅ Datos del autor completos (Massimo Sahonero, 6/11/25)

**programa.py:**
- ✅ Función `saludar()` con mensaje correcto: "¡Bienvenido al sistema de control de versiones!"
- ✅ Función `despedir()` con mensaje: "Hasta pronto!"
- ❌ **PROBLEMA**: Estructura incorrecta con dos bloques `if __name__ == "__main__":` separados
- ❌ **PROBLEMA**: Función `despedir()` mal posicionada e indentada
- ⚠️ El código necesita corrección estructural
