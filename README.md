[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Z6NE2ogx)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=16551855&assignment_repo_type=AssignmentRepo)
# Práctica 1: Introducción al desarrollo. Reflexiones.

Apoyate en los siguientes recursos para realizar la práctica:

[Descripción de la práctica](https://revilofe.github.io/section3/u01/practica/EDES-U1.-Practica010/)


---

# Título de la Actividad

## Identificación de la Actividad
- **ID de la Actividad:**  P1.1 - Reflexiones
- **Módulo:** `EDES` 
- **Unidad de Trabajo:**  P 1.10: Reflexión y discusión sobre los resultados
- **Fecha de Creación:** 15/10/2024 
- **Fecha de Entrega:** domingo, 20 de octubre de 2024, 23:59
- **Alumno(s):** 
  - **Nombre y Apellidos:** Daniel Felipe Oliveros Rojas 
  - **Correo electrónico:** doliroj929@g.educaand.es
  - **Iniciales del Alumno/Grupo:** DFOR

## Descripción de la Actividad
concretar los conocimientos del (tema 1) Introducción al desarrollo de software 

   ```

## Desarrollo de la Actividad
### Descripción del Desarrollo
[Explicación de cómo se ha abordado el desarrollo de la actividad, incluyendo las decisiones de diseño, estructura del código y enfoque de resolución de problemas. Se recomienda adjuntar diagramas o capturas de pantalla si es necesario.]



## Referencias y Fuentes
link



   ```

</> </> </> </> </> </> </> </> </> </> </> </> </> </> </> </> </> </> 



# Entorno de desarrollo

  
## P 1.10: Reflexión y discusión sobre los resultados


Entorno de desarrollo

  

## P 1.10: Reflexión y discusión sobre los resultados

### 1. Relación software y hardware

#### Primera parte

**1.1.1. ¿Cómo se ejecuta el código en el procesador?  
1.1.2. ¿Qué hace la memoria RAM con la información del botón o el LED?  
1.1.3. ¿Cómo se comunican los periféricos (botón y LED) con el procesador?**

**Segunda parte**

**1.2.1. ¿Cómo interactúan el procesador, la memoria y los periféricos en la ejecución del programa?**

En el disco duro : almacena de forma permanente los archivos ejecutables y los archivos de datos y las ram: almacena de forma temporal el código binario de los archivos ejecutables y los archivos de datos necesarios. Como ejemplo en Word, el software envía instrucciones al teclado (periférico) para captar las letras que estás presionando

**1.2.2. ¿Qué pasa con los datos en la memoria cuando el programa se ejecuta?**

En la memoria RAM guarda temporalmente la información mientras el programa sigue corriendo. Si decides guardar algún cambio, el procesador enviará instrucciones al disco duro para almacenar el cambio y poder recuperarlo más tarde.

**1.2.3. ¿Qué roles juegan las instrucciones del software en esta interacción?**

El rol mas importante es poder desarrollar aplicaciones eficientes. Si sabes qué recursos utiliza un programa, puedes optimizar el uso del procesador o la memoria, haciendo que el software funcione de manera más rápida y eficiente.

**1.2.4. ¿Cómo se relaciona esta simulación con lo que ocurre en un ordenador real?**

el software necesita comunicarse con el hardware, siguiendo unos pasos muy específicos. Al igual que una receta no tiene sentido sin alguien que la cocina, y alguien que cocina no tiene sentido sin receta. El hardware y el software se necesitan uno al otro.

  
  

**2. Del código fuente al ejecutable**

  
  

**2.1. ¿Cómo se diferencia el código fuente del código objeto y del ejecutable?**

**Código fuente (el "plano" que el programador escribe).**

**Código objeto** (las "piezas de madera" ya cortadas y listas para ensamblar).

**Código ejecutable** (la "mesa ensamblada" que puedes usar).

  
  

**2.2. ¿Por qué el ordenador no puede entender el código fuente directamente?**

Por que esta no esta escrito en código maquina y no lo puede leer directamente sin ser compilado

  
**2.3. ¿Por qué es importante el paso de enlazado en la creación de programas?**


El **enlazador** es una herramienta que toma los archivos de código objeto y los une en un solo archivo ejecutable. También incluye las bibliotecas para que el programa funcione correctamente

**2.4. ¿Qué ocurre si falta alguna de las etapas (código objeto o ejecutable)?**

Si falta una etapa de código objeto o ejecutable directamente no lo podemos usar en código fuente
### 3. Generación de código intermedio

**3.1. ¿Cómo difiere el código intermedio del código ejecutable tradicional?**

El código intermedio es traducido por a un lenguaje general ya que para que lo interprete el procesador lo tiene que intervenir una maquina virtual y en el ejecutable no, esta listo para usar

**3.2. ¿Por qué es útil tener una máquina virtual?**

Para que pueda ser interpretado o traducido a lenguaje maquina o de bajo nivel**  
3.3. ¿Qué ventajas ofrece el código intermedio?**

Que no esta orientado a un solo sistema de ejecución solo necesita una maquina virtual

**3.4. ¿Además de java, qué otros lenguajes usan máquinas virtuales?**

Java y c#

### 4. Lenguajes de programación

#### 4.1. Primera parte

Compara el proceso de ejecución entre el lenguaje **compilado** y el **interpretado**.  
**4.1.1. ¿Qué diferencias notaron en el proceso de compilación frente a la ejecución directa?**

Los lenguajes interpretados son son ejecutados linea por linea y los compilados

4.1.2. ¿Qué pasa si hay un error de sintaxis en cada lenguaje? ¿Cuándo se detecta el error?

#### 4.2. Segunda parte

Compara un lenguaje de **alto nivel** con uno de **bajo nivel**.  
4.2.1. ¿Qué notaron sobre la **abstracción** entre los lenguajes de alto nivel y bajo nivel?  
4.2.2. ¿Qué ventajas y desventajas encontraron en cada uno?

#### 4.3. Tercera parte

Compara un lenguaje **orientado a objetos** vs **funcional**.  
4.3.1. ¿Cómo funciona la organización de datos en Java usando objetos y métodos?  
4.3.2. ¿Cómo es diferente trabajar en un enfoque funcional en Python, usando solo funciones puras?

#### 4.4. Reflexión final

4.4.1. ¿Qué lenguajes se sintieron más fáciles de usar? ¿Por qué?  
4.4.2. ¿En qué casos es preferible usar un lenguaje compilado frente a uno interpretado?  
4.4.3. ¿Cuándo es mejor usar un lenguaje de alto nivel en lugar de uno de bajo nivel?  
4.4.4. ¿Cómo se siente trabajar con el paradigma orientado a objetos en comparación con el imperativo o funcional?

### 5. Herramientas de desarrollo

#### 5.1. Primera parte

Respecto a las proceso de creación de software identifica un conjunto de herramientas a usar.  
5.1.1. ¿Qué hace cada una de las herramientas?  
5.1.2. ¿Qué tipo de tareas facilita?  
5.1.3. ¿Qué características ofrece que la hacen única o diferente de otras herramientas similares?  
5.1.4. Elige una ¿Cómo es la experiencia de usuario al usarla? ¿Es fácil o compleja?  
5.1.5. Elige una ¿En qué situaciones sería ideal utilizar esta herramienta?  
5.1.6. Elige una ¿Qué limitaciones encontraste en la herramienta?

#### 5.2. Segunda parte

Céntrate en una herramienta dentro de la misma categoría y compárala con otras:  
5.2.1. ¿Qué herramienta se considera más útil y por qué?  
5.2.2. ¿Qué ventajas tiene una sobre la otra?  
5.2.3. ¿Cuál herramienta resultó ser la más intuitiva y por qué?  
5.2.4. ¿En qué casos se recomendaría usar un compilador en lugar de un intérprete?  
5.2.5. ¿Qué tipo de proyectos se beneficiarían más de un framework como Django?

#### 5.3. Reflexión final

Con base en la experiencia de evaluación de las herramientas:  
5.3.1. ¿Cómo crees que impacta la elección de la herramienta en la calidad del software?  
5.3.2. ¿Qué características buscarías en una herramienta para facilitar tu flujo de trabajo?  
5.3.3. ¿Cómo cambió tu percepción de estas herramientas después de haberlas probado y evaluado?