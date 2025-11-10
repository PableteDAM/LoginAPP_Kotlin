# 🖤 LoginApp – Interfaz de Inicio de Sesión con Jetpack Compose

Una aplicación sencilla desarrollada en **Kotlin** usando **Jetpack Compose**, que reproduce un diseño **oscuro y elegante** inspirado en Figma.  
El objetivo del proyecto es practicar el uso de `Composable` básicos y comprender la estructura visual de una pantalla de login moderna.

---

## 🎯 Características principales

✅ Interfaz 100% Jetpack Compose  
✅ Tema **oscuro elegante** (fondo #121212 y azul iOS #0A84FF)  
✅ Campos de **correo electrónico** y **contraseña**  
✅ Botón azul “Entrar” con esquinas redondeadas  
✅ Texto inferior con opción de registro  
✅ Código **limpio y fácil de entender** para principiantes

---

## 🧱 Estructura del proyecto

app/
├── java/
│ └── com.example.loginapp/
│ └── MainActivity.kt
├── res/
│ ├── values/
│ │ ├── colors.xml
│ │ ├── themes.xml
│ │ └── strings.xml
└── AndroidManifest.xml


El diseño se construye íntegramente dentro del archivo **MainActivity.kt**, utilizando componentes `Composable` como:

- `Text` → para los títulos y etiquetas  
- `OutlinedTextField` → para los campos de entrada  
- `Button` → para el botón de acceso  
- `Spacer` → para separar los elementos  
- `Column` y `Box` → para estructurar el layout  

---

## 💻 Captura de pantalla (Diseño aproximado)

