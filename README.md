![Programação-Java_ Persistencia de datos y consultas con Spring Data JPA](https://github.com/genesysR-dev/2066-java-persitencia-de-datos-y-consultas-con-Spring-JPA/assets/91544872/e0e3a9f8-afc7-4e7b-be83-469351ef2d70)

# ScreenMatch

Proyecto desarrollado durante el segundo curso de la formación Avanzando con Java de Alura

## 🔨 Objetivos del proyecto

* Avanzar en el proyecto Screenmatch, iniciado en el primer curso de la formación, creando un menú con varias opciones;
* Modelar las abstracciones de la aplicación a través de clases, enums, atributos y métodos;
* Consumir la API del ChatGPT(Opcional;
* Utilizar Spring Data JPA para persistir datos en la base de datos;
* Conocer varios tipos de bases de datos y utilizar PostgreSQL;
* Trabajar con varios tipos de consultas a la base de datos;
* Profundizar en la interfaz JPA Repository.


# 🎬 Screenmatch Backend API

Este proyecto es una API backend construida con **Spring Boot** que permite consultar información sobre películas y series utilizando la API pública de [OMDB](https://www.omdbapi.com/). Además, implementa persistencia de datos con **Spring Data JPA** y una funcionalidad de traducción automática al español utilizando **Google AI Studio**, ya que los resultados originales de OMDB se reciben en inglés.

## 🚀 Tecnologías utilizadas

- Java 17
- Spring Boot
- Spring Data JPA
- Database (modo desarrollo)
- API OMDB
- Google AI Studio (PaLM o Gemini para traducción)
- Maven

## 📦 Funcionalidades principales

- Consultar películas y series por nombre desde OMDB.
- Persistir los resultados en una base de datos.
- Traducir la información recibida al español automáticamente.


## 🔧 Configuración y ejecución

1. Clona el repositorio:

```bash
git clone https://github.com/JJGG1/screenmatch-backend.git
```

## ⚙️ Configuración del archivo `application.properties`

El archivo `application.properties` incluido en el repositorio contiene las variables de configuración necesarias, pero sin claves reales.

### Opciones para configurar la clave de OMDB:

- **Usar variables de entorno:**  
  Configura en tu sistema operativo una variable llamada `OMDB_API_KEY` con tu clave personal.  
  El archivo `application.properties` contiene la línea por ejemplo:  
  ```properties
  omdb.api.key=${OMDB_API_KEY}

De esta forma, la aplicación toma la clave directamente desde tu entorno y no necesitas modificar el archivo.

Configurar directamente en el archivo:
Alternativamente, puedes reemplazar la línea en application.properties con tu clave real:
  ```
  omdb.api.key=TU_CLAVE_AQUI
  ```

## Autores
|  [<img src="https://avatars.githubusercontent.com/u/127985134?s=96&v=4" width=115><br><sub>JJGG1</sub>](https://github.com/JJGG1) |
| :---: | 
