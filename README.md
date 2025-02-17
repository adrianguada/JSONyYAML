# YAML vs JSON: Características y comparación

## Introducción
**YAML** (Yet Another Markup Language) y **JSON** (JavaScript Object Notation) son dos formatos populares para la serialización de datos utilizados en  aplicaciones, intercambio de datos y otros para que sea legible por un humano.

---

## 1. ¿Qué es JSON?
JSON es un formato de intercambio de datos ligero y sencillo de leer para humanos y máquinas. Se basa en la sintaxis de objetos como en JavScript, aunque es independiente de este.

### Características principales:
- Utiliza una estructura basada en **Objetos** con dos elementos principales: **clave y valor**, puede contener varios pares seperaándolos con comas y dos puntos.
- Soporta diferentes tipos de datos a parte de los objetos, como **arrays, booleanos, strings y nulls**.
- Es ampliamente utilizado en **APIs web y bases de datos NoSQL**.
- Es compatible con la mayoría de los lenguajes de programación.

### Ejemplo de JSON:
```json
{
  "nombre": "Pedro",
  "apellidos": "Pedrosa, Pérez",
  "edad": 20,
  "ciudad": "Peñíscola",
}
```

---

## 2. ¿Qué es YAML?
YAML es un lenguaje de serialización de datos enfocado en la **legibilidad humana**, ya que es ampliamente utilizado para los **archivos de configuración**.

### Características principales:
- Usa una estructura basada en **indentación** en lugar de símbolos de formato habituales como llaves o corchetes.
- Es más fácil de leer y escribir en comparación con JSON.
- Soporta tipos de datos como **listas, números y booleanos**.
- Se emplea en herramientas y servicios de automatización como **Docker Compose y Ansible**.

### Ejemplo de YAML:
```yaml
nombre: Pedro
apellidos:
  - Pedrosa
  - Pérez
edad: 20
ciudad: Peñíscola
```

---

## 3. Comparación
| Característica  | JSON | YAML |
|---------------|------|------|
| **Legibilidad** | Legible para humanos | Más legible y limpio que JSON |
| **Estructura** | Usa llaves `{}` y corchetes `[]` | Usa indentación |
| **Comentarios** | No soporta comentarios | Soporta comentarios con `#` |
| **Uso común** | APIs, bases de datos NoSQL | Archivos de configuración y herramientas de automatización |
| **Compatibilidad** | Compatible con la mayoría de lenguajes | Menos compatibilidad en algunos lenguajes |

---

## 4. Conclusión
Ambos formatos tienen sus ventajas y desventajas. JSON es ideal para el intercambio de datos en la web, mientras que YAML es más adecuado para archivos de configuración debido a su simplicidad y claridad. La elección dependerá del caso de uso específico.

### Usa **JSON** cuando:
- Se necesite una estructura compacta y fácil de procesar por máquinas.
- Se esté trabajando con **APIs o bases de datos NoSQL**.
- Se requiera compatibilidad con la mayoría de lenguajes de programación.

### Usa **YAML** cuando:
- Se busque **una mejor legibilidad** para archivos de configuración.
- Se trabaje con herramientas como **Docker Compose o Ansible**.
- Se necesiten **comentarios en los archivos de configuración**.

---
