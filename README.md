# 🐍 Hack Python 1

Repositorio con la resolución de **10 ejercicios (hacks) de Python** orientados a practicar conceptos básicos del lenguaje: manipulación de strings, listas y bucles.

---

## 📋 Sobre el proyecto

Cada hack es una pequeña función que debe transformar una entrada en una salida específica. Todas las funciones se validan automáticamente con **pytest** mediante el archivo `test_hack.py`.

---

## 🛠️ Tecnologías

- **Python 3.14**
- **pytest** (para la validación de los ejercicios)

---

## 📂 Estructura del proyecto

hack_python_1/
├── hack_1.py          # Hack 1 - Función base
├── hack_2.py          # Hack 2 - Convertir a minúsculas
├── hack_3.py          # Hack 3 - Capitalizar primera letra
├── hack_4.py          # Hack 4 - Última letra en mayúscula
├── hack_5.py          # Hack 5 - Estilo "leet speak"
├── hack_6.py          # Hack 6 - Lista [0..5] con for
├── hack_7.py          # Hack 7 - Lista [5..0] con while
├── hack_8.py          # Hack 8 - Slicing de listas
├── hack_9.py          # Hack 9 - Intercalar elementos
├── hack_10.py         # Hack 10 - String a lista de caracteres
├── test_hack.py       # Tests con pytest
└── requirements.txt   # Dependencias del proyecto

---

## 🚀 Cómo ejecutar los tests

**1. Clonar el repositorio:**
```bash
git clone https://github.com/beto9v/hack_python_1.git
cd hack_python_1
```

**2. Instalar dependencias:**
```bash
pip install -r requirements.txt
```

**3. Ejecutar todos los tests:**
```bash
python -m pytest test_hack.py -v
```

**Ejecutar un test específico:**
```bash
python -m pytest test_hack.py::test_hack_1 -v
```

---

## 🧠 Conceptos practicados

- ✅ Métodos de strings: `.lower()`, `.upper()`, `.capitalize()`, `.replace()`
- ✅ Slicing de strings y listas
- ✅ Concatenación de strings
- ✅ Listas y método `.append()`
- ✅ Bucles `for` con `range()`
- ✅ Bucles `while` con condiciones
- ✅ Función `len()` y acceso por índice
- ✅ Conversión `list(string)`

---

## 👤 Autor

**Alberto Vargas**
- GitHub: [@beto9v](https://github.com/beto9v)

---

⭐ Si te resulta útil, no olvides dar una estrella al repo.