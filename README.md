
## Lee con atención todo el material.

---

<br/>

## **INTRODUCCIÓN**



Este desafío técnico es para repasar conceptos básicos sobre Javascript . El objetivo es que puedas chequear cuáles son tus conocimientos sólidos, y que conceptos podrías ajustar un poco más.

Lo ideal es que comiences a pulir tus habilidades de investigación, ya que en el mundo de la programación Google es nuestro mejor amigo, tengan en cuenta que durante esta cursada nosotros brindamos las herramientas y funcionalidades basicas, normalmente con ellas se podran cumplir las entregas pero nunca esta de mas investigar y aportar lo propio.

Es importante que puedas resolver todos los ejercicios que contiene este repositorio, así como también seguir todo el procedimiento a continuación.

---

<br />

## **¿CÓMO RESOLVER ESTA PRUEBA TÉCNICA?**

### **_1. CLONAR_**

El primer paso es clonar correctamente este repositorio en tu computadora.

Es importante que no hagas fork.

### **_2. INSTALAR DEPENDENCIAS Y CHEQUEAR TESTING_**

Desde tu terminal, dirígete al directorio en el que hayas clonado este repositorio. Una vez allí, tendrás que pararte en la carpeta raíz (la que envuelve todo), y ejecutar el siguiente comando para instalar las dependencias:

```bash
npm install
```

Luego de instalar las dependencias, tendrás que revisar si los testing funcionan correctamente. Si ves los tests fallando, ¡estás list@ para comenzar! Si no, lee bien la terminal para identificar el problema.

```bash
npm test
```

### **_3. RESOLVER LOS EJERCICIOS PROPUESTOS_**


-  `01.js`
-  `02.js`
-  `03.js`
-  `04.js`
-  `05.js`
-  `06-07-08.js`
-  `09.js`

### **_4. Si qures podes subir el desafio para que te quede guardado en github, pero la idea es que encuentren donde tienen dificultades y resolverlas en las primeras instacias de la cursada**

Si bien esta prueba es opcional y la entrega no es obligatoria, es muy importante que practiques este paso dado a que suele traer muchas dudas

Primero corre por última vez los test y verifica cuántos pasan para asegurarte de estar entregando todo correctamente. Luego tendrás que ejecutar los siguientes comandos desde tu terminal:

```bash
git add .
git commit -m ‘checkpoint commit’
git push origin main

```

### **😗 ¿Qué hay que hacer con el archivo package.json?**

Eviten tocar el package.json(Mas adelante en la cursada vamos a aprender que es y para que sirve, de momoento solo sigan las intrucciones)

---

<br />

## **GUÍA DE ERRORES COMUNES**

<p style="color: #f92850; font-weight: bold;">"jest" no se reconoce como un comando externo o interno...</p>

Si lees esto en la terminal, borrar la carpeta node_modules y el archivo package-lock.json y vuelve a ejecutar el comando:

```bash
npm install
```

<p style="color: #f92850; font-weight: bold;">1 failed, 1 total</p>

Debes tener un error de sintaxis. Revisa los ejercicios que hayas hecho, y asegúrate que no falte o sobre una llave, un paréntesis, un punto y coma, etc.

<p style="color: #f92850; font-weight: bold;">Author identity unknown</p>

Intenta ejecutar los siguientes comandos desde tu terminal para configurar tu cuenta:

```bash
git config –global user.name "_aquí escribe tu usuario de GitHub_"
Git config –global user.email "_aquí escribe tu email_"
git push origin main

```
## **DOCUMENTACIÓN**

Info que pueden ayudar a resolver los desafios

-  [String](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/String)
-  [Array](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Array)
-  [Object](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Object)
-  [Class](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Classes)
-  [Prototypes](https://developer.mozilla.org/es/docs/Learn/JavaScript/Objects/Object_prototypes)


