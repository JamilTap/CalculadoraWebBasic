# 🧮 Calculadora Web

Una calculadora web desarrollada con HTML, CSS y JavaScript puro. Incluye historial de operaciones y pruebas automatizadas usando **Jest** y **Mocha**.

> Calculadora Web (https://jamiltap.github.io/CalculadoraWebBasic/)
---

## 🚀 Demo
> 📂 Repositorio: https://github.com/Jamiltap/calculadora

---

## 📸 Capturas de pantalla
🖥️ Interfaz de la calculadora
<p float="left"> <img src="https://github.com/user-attachments/assets/bba3e4b2-5bc2-491d-96b2-e4678b4da90d" width="400"/> <img src="https://github.com/user-attachments/assets/588dfb74-5e9f-4901-a2f3-d1dfa25e4e1e" width="400"/> </p>
✅ Pruebas automatizadas (Jest y Mocha)
<p float="left"> <img src="https://github.com/user-attachments/assets/3206d7a0-0690-4002-9b2a-e44813665d16" width="400"/> <img src="https://github.com/user-attachments/assets/64d9df0b-2635-43ad-b999-578702056688" width="400"/> </p>
---

## ⚙️ Funcionalidades

- ✅ Operaciones básicas: suma, resta, multiplicación, división, porcentaje
- ✅ Agrupación con paréntesis
- ✅ Historial de operaciones
- ✅ Interfaz responsive
- ✅ Pruebas automatizadas unitarias

---

## 🛠️ Tecnologías usadas

- HTML5
- CSS3
- JavaScript (vanilla)
- Jest (testing)
- Mocha (testing alternativa)

---

## 📦 Instalación

1. Clona el repositorio:


git clone https://github.com/Jamiltap/calculadora.git

cd calculadora

2. Abre `index.html` en tu navegador.

## Cómo ejecutar pruebas
3.Instala las dependencias (si hay):
```bash
npm install --save-dev jest @testing-library/jest-dom jsdom
npm jest
```
## 🧪 Ejecutar Pruebas Jest
4. Extraer el archivo jest test y dejarlo en la carpeta del index, cambiar el script para el uso del framework
   
```bash
  "type": "module",
  "scripts": {
    "test": "jest"
  },
 
```
NOTA: debe marcarles unos 15 errores en ambos frameworks, eso son errores provocados por el desarrollador para comprobar el funcionamiento de ambos framework
---
5. Ejecuta las pruebas Jest con el siguiente comando en la terminal
```bash
npx jest
```
##  Ejecutar Pruebas Mocha
6. Extraer el  archivo "mocha test" y cambiar el una parte del codigo del Package.json,el "test" a Mocha
   
 ```bash
  "type": "module",
  "scripts": {
    "test": "Mocha"
  },
```
Debes borrar los archivos de las pruebas jest si no el framework mocha tendra un error remplazalo con el nuevo
```bash
npx test
```
## 📁 Estructura del proyecto
```bash
📦 calculadora/
├── src/
│   ├── index.html --Index base con pruebas unitarias
│   ├── styles.css
│   └── app.js     --Funcion logico de la calculadora
├── test/
│   ├── app.test.js --Codigo para pruebas basicas Jest y mocha
│   ├── pruebas.test.js --Codigo para pruebas con gran carga jest y mocha
│   ├── calculadora.test.js --Codigo para pruebas Jest si esta funcionando correctamente la calculadora en caso de JEST
│   └── Otros.etc
├── ....
├── package.json -- script para el uso del framework
├── jest.config.js
└── README.md
```
## 🧑‍💻 Autor
```bash
💼 GitHub: Jamiltap
```
## 📄 Licencia
