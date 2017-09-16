# Crea tu propio asistente inteligente usando API.AI

El mundo de los asistentes inteligentes crece día a día; Siri, Cortana, Alexa, Google Assistant y Facebook 'M' son algunos de los asistentes mas utilizados actualmente. Afortunadamente, esto a dado paso a que surgan nuevas API's y SDK's para que los desarrolladores puedan crear su propio asistente 100% personalizado y puedan implementar sus ideas e hacer integraciones a sus aplicaciones.

En este post nos vamos a enfocar en uno de los servicios mas utilizadas para la creación de asistentes inteligentes: Api.ia.
Con Api.ia podemos desarrollar de una forma bastante simple nuestro propio asistente con tan solo una sencilla configuracion inicial

## ¿Que es Api.ai?

Api.ai es un servicio que permite a los desarrolladores crear conversaciones de voz a texto, realizar procesamiento de lenguaje natural y crear sistemas artificialmente inteligentes que pueden ser entrenados y personalizados. Tiene una gran gama de bases de conocimiento existentes llamados Domains. Los Domains proporcionan una base entera del conocimiento, traducciones, tiempos y mas. En este articulo nos vamos a enfocar en entender este concepto de una forma mas profunda.

## Iniciando con Api.ai

Lo primero que tenemos que hacer es ir al sitio web de Api.ai y hacer clic en el botón que dice “Sign Up Free” que se encuentra en la pantalla inicial para crear nuestra cuenta.

![Sign Up for free](https://lh3.googleusercontent.com/fXtRq1O2CKbDi3SomhX1Dni4FCHww4twNZHkW5M_rsX4ptCLCoPmC0c35LvGz5XqKPDFeYrxgEpf68wfLj-okp9lu9DaeUFdfvEEcf-rPDuFb6hf8UY4-sIJ8oYzoP7Pu0PK4sD1Yip14k3JMO7t3CGFRdv7PlDFRtgtIEIU0F-nl0oTrf-XIfnJKryWmNcqTY9apFAZ7W_u0kYGW3ptKhdbS8XDZINqnHcOKcT7GZIGcFW-5flYS340jc1QcwRZWJr68v2Jd_vUGdiUOxVJ0U_bwRL3hch2O8zsCA7wATKvX6ng4C6ms_PlJP3giGPPBa7XCuYWuOcaRskr6t_U_ne9AdSr4UpbmZ0GCpx9F3A8XHYtY5O7HbeahQ_9xGYTkqr_T4h-EeJf7YanAYK4AJleFnf2o37ul91QS6hqngO6xiF_e7cCFCB3CHiPQsjYyu9oI4MBxFCdJYGzbJedfXTiS6MjQbAwnzg8Hruwc8CybIAfZqi6TtcJ2UGHKGm1t6P4kyeBMmSZx5um33eBC9cPOhNdFLlq3i6wWpATIo9U_tmBCUsCWFQoW5cPJQ=w2734-h1312 "Sign Up for free")

Al dar clic en este botón, este nos lleva a otra página para que podamos iniciar sesión utilizando nuestra cuenta de Google(1). Anteriormente se podia crear una cuenta utilizando tu email, pero a medida de que Api.ia fue comprado por Google, el inicio de sesión se migro hacia el uso exclusivo de cuentas de Google para  iniciar sesión. 

El siguiente paso es seleccionar nuestra cuenta de google (2), leer y aceptar las politicas/terminos de servicio:

|1 <img src="https://lh3.googleusercontent.com/p-EjUpMg_Goy5Cd-UvdkDGwSXI0P9dslhh5Bf5TOMe_ZWhKzC_CuaeztTu_jNq4UDjeDNqqtxz5q34e4WAtUWNu1JBIXZChKosS8HynT9KpMiNuxgsye7Q_GoaaQs4E0keKAlO7EqZQlgM1nMJCbt_UfXjzvVJWVbEt9e41RrANQvth7t5CZNBfB5h7zhhSN9_uMG_pakF-LsDGFL83R236aBZ-UUs24p_eP4xtyFSf8m821vwI5Qo-1uY9jfCrKmK99meQxxW-0heNc5CAUEz0SovMoca66cnt4hPxO5DmQB_mPIH5VzVZ6qLm9OG1_4L1cuWXhlpR9y8Ry4OjSPs_zlKDJRab0a3n1lZPgw8inJjoYTjtbFX19ciKqNvNqJ4_CwXvzLcqVu7kPiIGthqLEOYocsJJR9hw6XZ4tzAC5k2kFXXUYrMgpIR6Hie6Y2KnrBepOej20V-yBLF2bQuA4uojhXACCoETqcAlVREFXfyNo13yda9vVRLSyIjMR_gsY9Iy1kbs4eJmdbxHgEMx9ho02UroOlmp-Jp2ntXKW8ElXgHFtPOr7ZVPF7MGJRMbLXEfi=w2734-h1312" width="270">|2 <img src="https://lh3.googleusercontent.com/lA1bwuxcrOINXixpDXkMrT8FnsY4KS1_vjr8FDIaVOBpvvWdGPapzc4hR_-LnsTio5iiF9pE7T0Ezgz41z8N96unPrAhVahO3AflYAju24EqkU7nNBmELQE_zQ20RO0JEAw_Rg_7ADDbJhtg9KjrZDV2XJS_luo38SvxwJHMTPVUrw3j3AkJs6DYNDIh_QvIspN3MdVgSL21QYlwCU2G3LEifc8mEehH21YupwLTe7O-YQz6u3I0goOZqAMxMBrotQZ-6oFYs6x2iFMJkbh85xL6xT6-jShE9umd_Yjg-AAIjjxdhSTCztIlW4IURSZwXY4iFw4YU3mPo4N-hiETfTb6S3-2pANe-muCwrxn0PMpRCK6U1fK1qQin07pISdZ-d3nmmFGmwiN-fGw1D4tFUST0uXG0IngK4owmbeZL-H967ilZyT7AXbpx3UzPVtc-Fkz9m-JjL2pV8g0gs6tipCOLItTnpoaq6mougCCQieEtV7W6MfpQggNsv80Jcmk8AXsrWadiyZdQg0YjzTHU2NCM7jLTSLQfwNvdD4m4Rpb4O977yFbPKtchBMm0Q=w2776-h1358" width="270">|3 <img src="https://lh3.googleusercontent.com/4vCFCvD-EHzxU0X0HtxXsOr5kgPUMrkNO2iNgMzHM905RgZF1IkHxgWyFnzo0TfJm9I-4v3LkCgYwX2l8c5BxTaifLdIG2gELPRgtyifCARIeH-k_OQiCQcs1a8xnGsr_gLvqVITXXY_LqmCodNitQkPlV9uv6vdQkmxF29keUG3t4QTtiMlQ19Him6O6-tMB3G8CGJaA2QtVXojMJrg6xQbncku4IlrbzvoJwHHRCS13coqvJrET8VLhpdey3oRPApsZduCBnanKe3RYiYGKOISOG0FKRAO5RM_t0LQTddkn3wVhKyaHJry011efFMKcqjUN_dk8iAWLuWmzowVvt01LV5mRVMijgqzBDr92c7ell6t-ExuwIT62ZSss9InehRa9NH7MLjaaSsrybKXjz3fPWRVNKywy1OteSlA6XiDFt7FjjXRycBsI7C38bxJLrFhN_-faWAGQMaDbbtY7Bj-Xp6hz2BJ-Svg215mC7UxLENSYexhQusK6epdx0CwHH2F4XlPuzCc14DyLN1xdJmBYvpcljRjKChzRUo2ij2IjLGHVedK7ig9XZdNUg=w2734-h1312" width="270">|

Una vez registrado, el sitio de Api.ia te manda directamente a su interfaz en donde podras crear tu asistente virtual. Cada asistente que creas y entrenas se llama "agent". Por lo tanto, el siguiente paso es crear nuestro primer agente haciendo clic en el botón "Create new agent" que se encuentra en la parte superior izquierda:

![Create new agent](https://lh3.googleusercontent.com/oXkI_QHvh8hL2JqFFN_QIg5dA4F4jHw4oha5ryrwq-DABY29v_F9ye8M-ovxNB1un4OZueRSNT2v89OSNe0NEnmSUSyP8llALLY5J4KO2bZ1LXdzRD-ieA9RtB24tZ4i7ltmKrqYdvR6ogcGMji32KsYomSF3W0qLobLKfqBdmdLP5UhrMAlAWLAJGM_oenZx81ONx1bUW4ZJyHtkjOs7JA0WYdV638XAtyKuOl6Qv83TBUzF3M4drrS5UY-C5QPFOUTY8onbDybPcZC9q4XkoRYyJWkmE8qCbe2l5tB-_3AFSkzIEYsYSawIFVZVouLJE7-PqoAtWZGiaBs3jxZBgUQSagKEA1nPCtNrWncPpdwhvMybg466LUplQEqtB02KrvmYuK3JGBF0Q3w_ZOZuUAv2SP0CYvch8L4ePhKhuM1HYYL8IPyzuLCRhLkV0CUSQJ0J0RZwv6ETdKlU6QJ0sVQtn6975pvM2HkaUFxY4SESMQdcL7RdPBjeDA1WSJWSocWy-mkUL6SfTYhMqZBOrFdBU3riPwB-8ij6cmPvHureea_AVHuxDUEMNIgVg=w2776-h1358 "Create new agent")

En la siguiente pantalla, tenemos que poner los datos de nuestro agente:

* **Agent name**:  Agrega el nombre de tu agente, de esta forma puedes diferenciar cada uno de los agentes que tengas creados en Api.ia. Es recomendable que nombres a tu agente de acuerdo a las tareas que realizara, por ejemplo "English Teacher" o con un nombre propio, por ejemplo: Jorge.

* **Description**: En este campo debe de agregarse la especificacion de lo que realiza tu agente. Este campo es opcional y no es necesaria si el nombre de tu agente explica por sí mismo su funcion.

* **Language**: El idioma en el que funciona el agente. Una vez que hayas elegido el idioma no puedes cambiarlo. Para este tutorial utilizaremos inglés. Si quieres saber en cuales idiomas esta disponible Api.ia puedes revisarlo en la tabla de lenguajes que se encuentra en la documentacion de Api.ia.

* **Timezone**: 

Zona horaria: Como era de esperar, es el huso horario de su agente. Es probable que ya haya detectado su zona horaria actual.
También creará automáticamente un proyecto de Google Cloud Platform para su agente, por lo que no necesita hacer nada al respecto; todo está automatizado! Es bueno saber que esto está ocurriendo, sin embargo, si pasas por muchas pruebas y creas muchos agentes, solo sabes que hay una gran cantidad de proyectos de Google Cloud Platform que se están creando y que es posible que quieras limpiar algún día.


Timezone: As you’d expect, it’s the timezone for your agent. Chances are it’ll already have detected your current timezone.
It will also automatically set up a Google Cloud Platform project for your agent, so you don’t need to do anything in this regard; it’s all automated! It’s good to know this is happening, though, so if you go through a lot of testing and creating many agents, just know there are a lot of Google Cloud Platform projects being created which you might want to clean up some day.


Cuando haya introducido la configuración de su agente, seleccione "Guardar" junto al nombre del agente para guardar todo:







When you have input your agent’s settings, choose “Save” next to the agent’s name to save everything:


