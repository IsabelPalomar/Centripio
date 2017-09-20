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

* **Add sample data**: Api.ia provee una serie de ejemplos de datos que puedes agregar

* **Language**: El idioma en el que funciona el agente. Una vez que hayas elegido el idioma no puedes cambiarlo. Para este tutorial utilizaremos inglés. Si quieres saber en cuales idiomas esta disponible Api.ia puedes revisarlo en la tabla de lenguajes que se encuentra en la documentacion de Api.ia.

* **Timezone**: La mayoria de las ocasiones esta opción se agrega automáticamente, pero si no, es importante que agregues la zona horaria que estaras utilizando en tu agente.

* **Google Project**: En esta opcion puedes seleccionar un proyecto de Google Platform si ya tienes uno creado, de lo contrario Api.ia creara automaticamente un proyecto de Google Cloud Platform que sera utilizado posteriormente.

Una vez llenados estos campos, da clic en el boton de "Save" que se encuentra en la parte superior derecha de la interfaz. 

## La consola de prueba

Una vez que tengas tu agente creado, puedes empezar a probarlo en la consola que se encuentra del lado derecho. La consola te permite realizar consultas(queries) y enviarlas a tu agente, el agente te regresara el resultado de acuerdo a la informacion tenga disponible(1). Ingresa la pregunta: "How are you?" o cualquier otra para que pruebes esta funcionalidad(3): 

![The test console](https://lh3.googleusercontent.com/ttpNJMAXSWtvwCLBorAQzcpBFk81fng7QVJGt8Z5PKuFjBimtMhZR5d6AVIPyL6wlbXvE3sRF4e3trjMH5GyLaUEsjmRiZ3AVEP6CX7nZELhsmRxywdB94Mhk4ADikFgo0J8SOSYei9WIAq7-ttmYmt-6E6W87liyJdQpxO6bB2l4yG7diW7cmqHwkyuA3jDWIMYsnytwEdhoEFSNH_UqYP48nHsL5a6JQlhP9y4y6hdgSMeL4WqmKhXS0pWDkz4tnB_VGOE9FVSQPykPwfhOJh3Rp-R7WecHN6mWzHT5a3OxJFTVvGA1Cu66tbmFwrWyJS24sSYKzqPeOGXhyiXxlhCTcQLo886BVhThZ8NT4KX21hWomLg4aage1t8aoRHwGwyFwWinl_UdsoLGGD5McwIf31pIem2sw-PVqieCVdGfZUxmLI2oTT3dNvyMnmRUWt6Wo1PQSLOQ-44LhRtZPnIxj7CbIcnib00wqZTqrQ5dncj5PzM7o_74_F4zefXC7Sw2ngFrpQckM996mUB6rc63_edqKA0jQvPoV7G35CVTfbStecuGbRBAQWwrA=w2776-h1358 "The test console")

Cuando realizas una consulta Api.ia te mostrara todos los detalles de los resultados. En la parte de abajo, se muestra un botón que dice "Show JSON". Haz clic en él para ver cómo la API regresa los resultados:

|1 <img src="https://lh3.googleusercontent.com/IC-7gm72T813PDdzePRP0pnjZTmnkWU7VhhwmSaHRQUqMBxGBm-IJeXlZ30B9YHlY3Xz5nccBhBy8d9g18pW6P6bvi9ma-JoqWw1-q4Liur6IyMd3lGNRUOuZjreZPEk1m5ibfDe4bZ1i7m0We-eijTrBcQ5uKao0DdpGdnIgIiMXCnOaFXR9V7uD-TzXTTQTgjN6AOA_WOsTispiTblfE2LWLaBRe8GQjGSW3vn2CXAe4sxk4WR00tsJUO7g3az0NhQvGGrlG5S8gFm-aJvHc95WHw0q0HrSF0znhSa8xB3TlE-gnitWYwMuX9TiugYU3YdZvi2fn9IzjB--bEHiH6PC47R-HXTOFjdk3x3M4nPNG6b2oKrKU-s2NQbgwKm4V4_m2y2QSc8yGgW79QcU_4UZrfhzhdbWXlzVxqfo3LeTAnyIxUP7KYOCh_tJOwY_KAe9S8mzEXhCvf6OaRLkmZWW6cbUFw6OsGRDG5_Xs5fdsEkVwL-9aRqvsTpcXzx5iSQROPhrgj-AQNBkrmzgk-T4RgoRXBiUDvCBZ1H7uh0YBYR4labc8rWwCCJxw=w2776-h1358" width="290">|2 <img src="https://lh3.googleusercontent.com/dWZvC9SDyRYr7BGtowpuFdXHT5RBvpD5tFS378lKQsNR8sFvU6MOu2iFUWub1LrQLBv0eQgevBuIA7YIWDg19toTy9St0IIO_jqr4o7fufB9k3M19MjYIH-ebDBbVuXsgJXz-A067t7G8ei9j7juBCTYDf-rbnv9e4a9-TQZmYMzECJnYZyxxkS9NwFtvNRbiS-YgRfd25UJD8Bzg70ik9WGtgfOeELHMGOvxJVWcrS6QCSltDkQVqKlI8yPpk_azzZF70KSudQyJSSaTTEbxqZd9IrUv3m2QSMXBN0YH-Bn_bRUEMu8ZfETRGz0mEbeCP2YBQKo3HZSot24FTXqE_F-dGGGlGVdin48fiYr30MSH-SOCX7liW4MIaH3smXyhgx3RFyXD-LLUNe76pctUCC7IRj6t0UzWJTW3uj8-sVdJ-vFYJB7MSCoOXRGz7S9k0uUCBP5W44JB8bZKz5HTF2wVOXKClpBSuQIOUAro_oJy2g-XScofmJG9M87yfG4ZAMijX2zyjPQVJpYQBipuCSyVq-NqgoMZySLsXZa5qGqlIl1gma2Oz7kfsJY9Q=w2776-h1358" width="300">|

Si revisas la respuesta de tu agente podrás observar que hasta ahora no sabe cómo responder, aún necesita que le agregues la lógica con la funcionalidad que necesites. El valor de **input.unknown** nos indica que aun no sabe cómo proceder y por default ahora esta mostrando el mensaje que dice “Sorry, can you say that again?”. La lógica de las respuestas de un "Agent" se agregan en la sección de **"Intents"** que se encuentra en el menu izquierdo.

## Small Talk

Api.ia provee una funcionalidad que nos permite agregarle un pequeño toque de inteligencia a nuestro asistente: **"Small Talk".**  Con Small Talk podemos proporcionar una gama de respuestas para preguntas frecuentes, por ejemplo, para la pregunta que hicimos anteriormente: "How are you?". Por default esta opción no se encuentra activada, para agregarle esta funcionalidad a tu agente solo necesitas hacer click en la opción de “Small Talk” que se encuentra en el menu izquierdo y seleccionar la opcion que dice: "Enable"

![Small talk](https://lh3.googleusercontent.com/9t5YmUv5Wv4YX0p_uDqQC_np76wEMbCeQw2yyvlA7bfxoM4_zwbihlr-By2PZhFacYlLyQ4SZEK4rhMzzPq15kXDcQzyXpUZlvdB6siDhVnKdHQvY4znLwH-3hnTGniGHExzOFET7_yoDQ5tuwuRSEpmX6_7EUUZ9O-HsFMij4bJhXhA7w6h2-k-akO28hPMdb61YMzcQbv9irTX5sW0RrWHsDF-eygLfxQf_JO9ELItowY9npcVT0hugxBS4WHrzc-qvtCvkNA2afBwCcNGCghVBHKlVlRoQ-cc-M8G536SpOc3ipqwx5ACjMYCdiHBJtjI5kR6GPN62TV_erKfSHGChwe6wOjEJnOWJ10CRYe6DJ8Rwvha29F3rFVrAVwmqpgieaVALckUj8gMDdzd1JGNvxBDD3ULZNEKpaViLIA1Hemf8tOGdppuQwsEPrs3yheKZyPXwNsGFQNRO1t0yfpTzp-uplMYns_WVQKso01t3PVD7TLOqOLlrF0uPN47G0lE9G3fMG8LU-ZB0XFtskvIPz5bEDnGlWGz0iZyifQthuWDSmorr5iKu0Gc6Q=w2734-h1312 "Small Talk")

Después de habilitar esta funcionalidad podras observar que se despliegan una seria de categorías con frases comunes en "Small Talk". Encuentra la seccion que dice "Hello/Goodbye" y dale clic para expandirla. Agrega diferentes respuestas y despues haz clic en el botón "Save" que se encuentra en la parte superior para guardar tus respuestas. Cada vez que añades frases, la cifra del porcentaje que se encuentra a lado de cada categoría irá aumentando para mostrar que tanto has personalizado tu chatbot:

![Small talk personalization](https://lh3.googleusercontent.com/5Nlu5DSv5wTEIyeCjLm6p7kLThtMybyHBQ87dQs---eSLHzupfsr2Wznc_al09uaJspy-CTuqtnEtDSA3SJp0U7PHC1ptLKQYdLLEy5U4QFa1F2Y0C3t5Y0pZMU1WmfQBI741ooe0k-rkZ4DXb1yeMDVUDH-s7UWamAg0cpD2eBbvHQxBayO93MJy35r6badJMTuE3TyYRZM9rJIU-o--B-GPuOrOlU9Uv6X2ZMG9Itnoj1vaUv_lSvsX48LRwM7R4XxyAvqAhEjxev6qwv3h2RxzVdnVidRWr1VN5U7xMSTWQHMObTGdxlw6p8OAeiiA7sssgLkbFHeCeYK81Zp0eiOFP3uY5ZgoWJhmIquOvdzAmODbfJxMXY0KnUJYYTr1Ylttf06IDK3HW3DUERIiZuauHCZa_VHZnoEaMeKW_XJRB5KHz90nz3BWTa8jKra1uGYRmVR_hO3Rzuj_VgUKyhdRi-yzp0dnTvyMpc8w5EjAUxsY0WvclCjUFtYRdFz3U8iU9lAkmQRTKwZxqLv9_vbvAB0DA1tqXNgooMZqWNptgS8_nuQ6lxSkChIxA=w2776-h1462 "Small talk personalization")

Si vas ahora a la consola de prueba y le preguntas a tu asistente “How are you?” nuevamente, este te responderá con las diferentes opciones que le agregaste.

![Small talk responses](https://lh3.googleusercontent.com/DkNXxCbifxLNxRABmRLYJZn1zzTnjRocfz3ZGvCxD5eEVZ1ibJCCgslm-JpPG5tOKrtKBcjyfpq9Tgd9zlEl8wFvAjq8qB-4daTsJPk5ZN--bwAJ-SqJLGqDrwAwspREsGJp3KQbv-ekhiV3AB2N1OlUnF_i8ODP6C-3YJxM6eOZmraIKRC97y-VOlOc4Muj3PFBXxjcvRylHEsMrRKhHqFztwL32mZA81pSuJhfsNfAN9vwV9VMNMzoaPpPWo3UBMH6gFpTv0q4mKyX0uQTbJJ_WXkIeQar9JJgDdVNFcqs_haLNSlCkoHIumdEBlT5n5-uROS1VZvePQis2UoY-MjFN431rwdrQfymajpqBJwHwq-13TKpoRePx2-c1LBTq6lEKMHS64NqYgd0x79IFIwDDDp2070r4dQjtY1g2h-LTsZP4iyBwHchPrW28mZiDGoJCtHPYybYZO15a57BzELHgkm-gjNIPXxO9Mpmm7PDMwKvgabCimwealCrmlQr7VHcojvHEsugfnk584GNU2YPpRB2ypTctdRWaht9_pwBGmuZzmV8Y9dCAP1rjQ=w2734-h1312 "Small talk responses")

Si tu agente no esta respondiendo correctamente, comprueba que si hiciste clic en el botón de "Save" ya que los cambios no se guardan automáticamente.

Lo que hará diferente a tu agente de otros es que tenga una personalidad única, en otras palabras, entre mas adaptado y personalizado tu agente podrá responder mejor a sus usuarios. Con Api.ia puedes elegir el tono y la estructura de las respuestas, por ejemplo, si es un chatbot que ama los gatos tendrá que responder cosas relacionadas con los gatos o si es un chatbot de una aerolínea que ayuda a los usuarios este deberá responder cosas relacionadas a la ayuda que se espera que proporcione.

Ahora que tu asistente ya es capaz de responder conversaciones pequeñas podemos empezar a integrarlo con su propia interfaz web. Para ello, necesitamos las "API keys" para poder tener acceso al agente.

## Api.ai API keys

Las "API keys" se encuentran en la página de configuraciones de tu agente, para encontrarlas solo tienes que hacer clic en el ícono que se encuentra a un lado del nombre de tu agente. Por ahora el valor que necesitamos es el de “Client access token”, este es un token único que te permite hacer consultas al servicio de Api.ia. 

![API keys](https://lh3.googleusercontent.com/h9URGTQ0BN_GmDTAK33DW8TAo_OZftheeQp63zCvef4ljcZLl8ZmsUstFK4yK3Pa7TyjXip3wBIwcyEGI42HXFokKXzyl74Yh28BhdtnlzypYcYDdkrpA1KbGY65NLCYkgQhJ5e2Qs0iP_rmaqeb2jU62PZVI8lGpUNKCMzGha4Ih0DazPUDthhtbHhojuFacgcjwFO7KwmcLG3M27K9nq1wMNjG--z2GSf8IFUWh1bXR61cRfF6zf89f3WqaAsoJbLHCzyiKsGxiFtfovZ9n97QbOFlQ1i-apLoDrUM4GGdQlfAOGj5MjidH8ZAi1j3KPuOc6yhkNETAalny_vtQ9p3xX1CmTjYO4tOPgbGbY0t1R4gTKeFGEDvBTLt5GQjNrxn6EBVEYH5OrhK_57fxghsNgV8G3CdAcTJ0Yn7r6u_91SYALwbfqUsvcvkPNHYyY7FxAG1EebNTDfqL4vVpFSnUHvKvoPs-0BytmOSXY4qufXRvLfH98PjNeRa98FvmZ0vgFdSthkndzpMBL0CVoeFjORxudi-TShcoVRxtV3SoIciYfKS-KAbL1QwmA=w2734-h1400 "API keys")

## Let's code!

¡Llegó el momento del código! Para empezar puedes descargar el codigo que se encuentra en este repositorio de Github: https://github.com/IsabelPalomar/demos-api-ia/tree/master/01-mi-primer-asistente. Sientanse libre de utilizarlo como base y desarrollar nuevas opciones para su asistente personal, más adelante explicaremos el código paso a paso.

Si quieres verlo en acción puedes ver al asistente funcionando funcionando aqui:





