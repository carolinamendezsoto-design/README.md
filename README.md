# 📘 "Alke Wallet"  
## Fundamentos del Desarrollo Frontend

---

## 🧾 Descripción del proyecto

Este proyecto corresponde al **Trabajo Práctico del Módulo 2 – Fundamentos del Desarrollo Frontend**.  
Consiste en el desarrollo de una **billetera virtual (wallet)** simulada, realizada únicamente con tecnologías frontend.

La aplicación permite realizar operaciones básicas de una billetera digital sin conexión a backend, utilizando almacenamiento local del navegador.

---

## 🛠️ Tecnologías utilizadas

- HTML5  
- CSS3  
- JavaScript  
- jQuery  
- Bootstrap 5  
- localStorage  

---

## 🚀 Funcionalidades

### 🔐 Login
- Inicio de sesión con credenciales predefinidas.
- Al autenticar, se guarda el usuario activo en localStorage.
- Redirección automática al menú principal.

### 📋 Menú principal
- Visualización del usuario conectado.
- Visualización del saldo disponible.
- Acceso a las distintas operaciones.
- Opción de cierre de sesión.

### 💰 Depósito
- Permite ingresar un monto válido.
- Actualiza el saldo disponible.
- Registra el movimiento en el historial.
- Redirección automática al menú principal.

### 💸 Retiro
- Permite retirar dinero validando el saldo disponible.
- Actualiza el saldo.
- Registra el movimiento como retiro.
- Redirección automática al menú principal.

### 🔄 Envío de dinero
- Simulación de envío de dinero a un contacto.
- Descuento automático del saldo.
- Registro del movimiento como transferencia.
- Redirección automática al menú principal.

### 📊 Historial de movimientos
- Visualización de todos los movimientos realizados.
- Filtro por tipo de movimiento:
  - Depósito
  - Retiro
  - Transferencia

---

## 💾 Almacenamiento de datos

La aplicación utiliza **localStorage** para almacenar:

- Usuario activo  
- Saldo disponible  
- Historial de movimientos  

No se utiliza base de datos ni backend, ya que el objetivo del proyecto es practicar **desarrollo frontend**.

---

## ▶️ Cómo ejecutar el proyecto

1. Descargar o clonar el repositorio.
2. Abrir el archivo **Login.html** en el navegador.
3. Utilizar las siguientes credenciales:
 Email: Lizz@gmail.com
 Contraseña: 1234

4. Navegar por las distintas funcionalidades desde el menú principal.

---
## 📁 Estructura del proyecto

Login.html
Menu.html
Deposit.html
Withdraw.html
SendMoney.html
Transactions.html
README.md

---

## 📝 Observaciones

- El proyecto fue desarrollado respetando las consignas del Módulo 2.
- Se utilizaron únicamente tecnologías vistas durante el curso.
- Se priorizó la claridad del código y la experiencia del usuario.
- Las redirecciones se realizan mediante JavaScript con temporizador.

---

## 👤 Autor

Trabajo realizado por:  
**Carolina de los Ángeles Méndez Soto**

---

## 🎓 Curso

**Fundamentos del Desarrollo Frontend – Módulo 2**





