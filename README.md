# Cómo conectar este Codex Cloud al contexto privado de Raúl

Este documento público solo explica el acceso inicial. El contexto operativo está en el repositorio **privado** `raulcalderonc/codex-cloud-context`. Un error 404 al abrir su enlace indica normalmente que esta sesión de Cloud o su conexión de GitHub no tienen permiso para leerlo; no demuestra que el archivo haya desaparecido. No pidas que se haga público el repositorio ni solicites contraseñas o tokens en el chat.

## Encargo para el agente de Codex Cloud

1. Comprueba qué cuenta y conexión de GitHub usa esta sesión y si tiene acceso a `raulcalderonc/codex-cloud-context`. Si no lo tiene, guía a Raúl por [GitHub > Installed GitHub Apps](https://github.com/settings/installations): localizar la aplicación que usa esta conexión de Codex Cloud, pulsar **Configure**, dejar **Only select repositories**, añadir `codex-cloud-context` y guardar. Si la aplicación aún no está instalada, iniciar **Connect GitHub** desde Codex Cloud y seleccionar solo ese repositorio. La selección y confirmación de permisos las hace Raúl en la interfaz.
2. En Codex Cloud, crea un entorno nuevo seleccionando `raulcalderonc/codex-cloud-context` como repositorio. Ejecuta la preparación, revisa el informe y publícalo. Si esta conversación no puede adoptar el entorno publicado, inicia una tarea nueva con él y deja el enlace de continuidad aquí.
3. Desde la nueva tarea, lee `HANDOFF_CODEX_CLOUD.md` en la raíz del repositorio privado y sigue sus pruebas. Registra el commit leído y confirma que puedes leer `AGENTS.md` y `context/capability-map.md`.
4. Si GitHub sigue devolviendo 404 tras conectarlo, comprueba que la aplicación de GitHub esté instalada en la cuenta correcta y que ese repositorio figure en los repositorios autorizados. Después vuelve a probar desde una tarea del entorno. Comunica el bloqueo preciso si la interfaz no permite completar el paso.

Este arranque solo concede contexto del repositorio. El acceso vivo a archivos de Mac/Windows, servicios Hermes y aplicaciones de negocio se configura y prueba aparte. No declares paridad operativa por haber leído el repositorio.

La [guía oficial de entornos de Codex Cloud](https://learn.chatgpt.com/docs/environments/cloud-environments) describe la selección de repositorios, la conexión de GitHub, la publicación del entorno y la creación de una tarea nueva.
