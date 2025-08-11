## 🧮 Calculadora Web – Comparativa Jest vs Mocha
Una calculadora web desarrollada con HTML, CSS y JavaScript puro, utilizada como módulo experimental para comparar Jest y Mocha como frameworks de pruebas unitarias en proyectos JavaScript.
Incluye historial de operaciones, interfaz responsive y pruebas automatizadas.

🌐 Demo: > Calculadora Web (https://jamiltap.github.io/CalculadoraWebBasic/)
---
📂 Repositorio: GitHub
---
📖 Descripción del estudio
En el Instituto Superior Tecnológico Tena se identificó la necesidad de establecer criterios comparativos para determinar cuál framework de pruebas unitarias se adapta mejor al desarrollo de aplicaciones frontend.

Este proyecto compara Jest y Mocha, evaluando:

> Rendimiento
> Facilidad de uso
> Adaptabilidad en entornos de desarrollo
> Como caso de estudio, se desarrolló una calculadora web y se aplicaron pruebas unitarias para:
> Validar operaciones básicas
> Manejar errores
> Controlar entradas inválidas


## 📊 Resultados
Métrica	Jest	Mocha
Tiempo de ejecución total	3,2 s (incluye métricas)	3 ms (sin arranque del entorno)
Configuración inicial	Sencilla, integrada	Requiere configuración extra
Librerías extra	No necesarias	Necesita Chai u otras
Cobertura de código	Integrada	Requiere configuración
Claridad en reportes	Alta	Media
Flexibilidad	Media	Alta

Conclusiones:

Jest es ideal para entornos educativos y proyectos ágiles.

Mocha es mejor para desarrollos que requieren personalización y control granular.

Las pruebas automatizadas, junto con estándares como ISO/IEC 25010 e ISO/IEC/IEEE 29119, mejoran la calidad del software.

## 🖥️ Capturas de pantalla
Interfaz de la calculadora

<p float="left"> <img src="https://github.com/user-attachments/assets/bba3e4b2-5bc2-491d-96b2-e4678b4da90d" width="400"/> <img src="https://github.com/user-attachments/assets/588dfb74-5e9f-4901-a2f3-d1dfa25e4e1e" width="400"/> </p>
Pruebas automatizadas (Jest y Mocha)

<p float="left"> <img src="https://github.com/user-attachments/assets/3206d7a0-0690-4002-9b2a-e44813665d16" width="400"/> <img src="https://github.com/user-attachments/assets/64d9df0b-2635-43ad-b999-578702056688" width="400"/> </p>
 ## ⚙️ Funcionalidades
✅ Operaciones básicas (suma, resta, multiplicación, división, porcentaje)

✅ Agrupación con paréntesis

✅ Historial de operaciones

✅ Interfaz responsive

✅ Pruebas automatizadas con Jest y Mocha

## 🛠️ Tecnologías usadas
HTML5

CSS3

JavaScript (vanilla)

Jest (testing)

Mocha + Chai (testing alternativa)

## 📦 Instalación y ejecución
```bash
npm install --save-dev jest @testing-library/jest-dom jsdom
npm jestbash
npm install --save-dev jest @testing-library/jest-dom jsdom
npm jest
```
---
# Clonar repositorio
git clone https://github.com/Jamiltap/calculadora.git
cd calculadora

# Abrir en navegador
index.html
## 🧪 Ejecutar pruebas
Jest
```bash

npm install --save-dev jest @testing-library/jest-dom jsdom
npm test
```
Mocha
```bash
npm install --save-dev mocha chai
npm test
```
## 📁 Estructura del proyecto

## 📦 calculadora/
```bash
├── src/
│   ├── index.html        # Interfaz principal
│   ├── styles.css        # Estilos
│   └── app.js            # Lógica de la calculadora
├── test/
│   ├── app.test.js       # Pruebas básicas Jest/Mocha
│   ├── pruebas.test.js   # Pruebas de carga
│   ├── calculadora.test.js # Validación Jest
├── package.json
├── jest.config.js
└── README.md
```
## 👨‍💻 Autor
Jamil Tapia
📧 Contacto
