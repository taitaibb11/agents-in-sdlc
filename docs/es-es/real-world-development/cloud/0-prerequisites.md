---
title: "Ejercicio 0: Requisitos previos"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

Antes de comenzar los ejercicios con el agente en la nube de Copilot, prepara lo necesario. Crearás una copia del repositorio de Tailspin Toys e iniciarás un [codespace][codespaces]. En este entorno editarás archivos de instrucciones y revisarás el trabajo del agente en la nube.

## Configurar el repositorio del taller

Utiliza la [plantilla][template-repository] para crear una copia del repositorio donde trabajarás. El nuevo repositorio incluye todos los archivos necesarios para los ejercicios y lo utilizarás durante el taller.

1. En una nueva ventana del navegador, abre la [plantilla de Tailspin Toys][tailspin-template].
2. En la página del repositorio de prácticas, selecciona **Use this template** y, después, **Create a new repository** para crear una copia del repositorio.

    ![Botón Use this template](../../../_images/ex0-use-template.png)

3. Si participas en el taller durante un evento organizado por GitHub o Microsoft, sigue las indicaciones del mentor. De lo contrario, crea el repositorio en una organización con acceso a GitHub Copilot.

    ![Formulario para especificar la configuración del repositorio de la plantilla](../../../_images/ex0-repository-settings.png)

4. Anota la ruta del repositorio que has creado (**organization-or-user-name/repository-name**) para consultarla más adelante.

## Crear un codespace

Ahora trabajarás en el taller desde un codespace.

[GitHub Codespaces][codespaces] es un entorno de desarrollo basado en la nube que permite escribir, ejecutar y depurar código en el navegador. Proporciona un IDE completo con compatibilidad para varios lenguajes de programación, extensiones y herramientas.

1. Abre el repositorio que acabas de crear.
2. Selecciona el botón verde **Code**.

    ![Seleccionar el botón Code](../../../_images/ex0-code-button.png)

3. Selecciona la pestaña **Codespaces** y, después, el botón **+** para crear un codespace.

    ![Crear un codespace nuevo](../../../_images/ex0-create-codespace.png)

La creación del codespace puede tardar unos minutos, pero es mucho más rápida que instalar todos los servicios manualmente. Mientras esperas, puedes explorar otras funciones de GitHub Copilot; las descubrirás en los pasos siguientes.

> [!CAUTION]
> Volverás a utilizar este codespace en ejercicios posteriores. Por ahora, déjalo abierto en una pestaña del navegador.

> [!NOTE]
> Este taller está preparado para ejecutarse en Codespaces o en un contenedor de desarrollo [dev container][dev-containers] local. Ambos entornos proporcionan los requisitos previos necesarios para seguir los pasos sin problemas. Para trabajar localmente, abre el repositorio clonado en VS Code y selecciona **Reopen in Container** cuando se te solicite. VS Code creará el mismo contenedor de desarrollo que Codespaces.

[codespaces]: https://github.com/features/codespaces
[dev-containers]: https://code.visualstudio.com/docs/devcontainers/containers

## Resumen

Has creado una copia del repositorio del taller e iniciado la creación de un codespace. Utilizarás este entorno para trabajar con el agente en la nube de Copilot.

## Siguiente paso

Añade instrucciones personalizadas que seguirá el agente en la nube. Continúa con el [Ejercicio 1: Instrucciones personalizadas][next-lesson].

## Recursos

- [Información general sobre GitHub Codespaces][codespaces]
- [Crear un repositorio a partir de una plantilla][template-repository]
- [Inicio rápido de Codespaces][codespaces-quickstart]

[tailspin-template]: https://github.com/github-samples/tailspin-toys
[template-repository]: https://docs.github.com/repositories/creating-and-managing-repositories/creating-a-template-repository
[codespaces-quickstart]: https://docs.github.com/codespaces/getting-started/quickstart
[next-lesson]: ../1-custom-instructions/
