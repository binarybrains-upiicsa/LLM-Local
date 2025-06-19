# LLM-Local: Ejecuta Mistral:7b en tu Computadora

Bienvenido al repositorio **LLM-Local**, un proyecto diseñado para la comunidad interesada en ejecutar modelos de lenguaje grandes (LLM) de manera local en sus computadoras. Este repositorio proporciona una guía detallada y paso a paso sobre cómo instalar y configurar el modelo Mistral:7b con la ayuda de OLLAMA en tu máquina local.

Conoce más acerca de [Mistral](https://mistral.ai/), sus LLM's e iniciativas.

![image](https://github.com/user-attachments/assets/ae3922a2-38b6-43ac-b6c4-d094c68e1693)

## ¿Qué encontrarás en este repositorio?

| Sección | Descripción |
|---------|-------------|
| **Guías de Instalación** | Instrucciones para instalar Mistral:7b en tu computadora. |
| **Configuración Inicial** | Pasos detallados para configurar el entorno necesario y preparar tu terminal para ejecutar el modelo. |
| **Ejemplos de Uso** | Ejemplos prácticos y comandos para interactuar con Mistral:7b a través de la terminal. |
| **Experimentos** | Ideas y sugerencias para experimentar con el modelo y sacarle el máximo provecho. |

## Objetivo

El objetivo de este repositorio es democratizar el acceso a tecnologías avanzadas de inteligencia artificial, permitiendo a los usuarios ejecutar y experimentar con modelos de lenguaje grandes sin necesidad de recursos en la nube. ¡Únete a nuestra comunidad y comienza a explorar el fascinante mundo de los LLM locales!


# Guía de Instalación de Mistral:7b con OLLAMA

Esta guía te llevará a través de los pasos necesarios para instalar y ejecutar el modelo Mistral:7b en tu computadora local utilizando OLLAMA.

## Paso 1: Instalar OLLAMA

Sigue estos pasos para instalar OLLAMA en tu sistema:

1. Descarga la última versión de OLLAMA desde el [sitio oficial](https://ollama.com/).
2. Sigue las instrucciones de instalación específicas para tu sistema operativo.

## Paso 2: Configurar el Entorno

Configura el entorno necesario para ejecutar Mistral:7b:

1. Abre una terminal.
2. Ejecuta el siguiente comando para verificar la instalación:

```bash
ollama --version
```

![image](https://github.com/user-attachments/assets/7eebebf5-b392-4719-8e6f-37ce0064d481)

## Paso 3: Descargar Mistral:7b

Una vez que el entorno esté configurado, puedes ejecutar Mistral:7b con el siguiente comando:
La descarga del modelo puede tardar un poco. 
```bash
ollama run mistral:7b
```
![image](https://github.com/user-attachments/assets/e8cb34f8-7f6d-43f6-bada-7f32d7a7dd2f)


## Paso 4: Verificar la Instalación

Para verificar que Mistral:7b se instaló correctamente y posteriormente ejecutarlo, puedes usar los siguientes comandos para interactuar con el modelo:

```bash
ollama list
```

![image](https://github.com/user-attachments/assets/54e8659e-5d09-4ba3-a8ea-5209aa6badac)


```bash
ollama run mistral:7b
```

## Ejemplos de Uso

Aquí tienes algunos ejemplos prácticos de cómo interactuar con Mistral:7b:

- **Generar Código:**

```bash
ollama run mistral:7b "Genera un código en python donde a traves de un bucle repita la frase "Bienvenidos a Binary Brains, a traves de Mistral 7b""
```
![image](https://github.com/user-attachments/assets/dae26da2-5e76-432e-b23a-fd6f870aa8df)

- **Responder Preguntas:**

```bash
ollama run mistral:7b "¿Cuál es la capital de Francia?"
```

![image](https://github.com/user-attachments/assets/7b348c44-abd1-499e-99b1-ccf9515c3344)


## Experimenta y Explora

¡No dudes en experimentar con diferentes comandos y configuraciones para sacarle el máximo provecho a Mistral:7b! Si tienes alguna pregunta o sugerencia, no dudes en abrir un issue en este repositorio.

## Contribuciones

Si deseas contribuir a este proyecto, por favor abre un pull request con tus cambios. Estamos encantados de recibir contribuciones de la comunidad.
