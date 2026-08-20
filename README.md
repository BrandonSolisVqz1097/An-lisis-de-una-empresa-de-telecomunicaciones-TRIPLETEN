# An-lisis-de-una-empresa-de-telecomunicaciones-TRIPLETEN
Análisis exploratorio de datos de uso móvil (llamadas y mensajes) de ConnectaTel, empresa de telecomunicaciones en México y Colombia. Incluye limpieza de datos, detección de outliers y segmentación de clientes por edad y nivel de consumo, con Python (pandas, seaborn, matplotlib) en Jupyter Notebook.

El objetivo de la empresa es identificar patrones de uso, detectar comportamientos atípicos y comprender qué segmentos de clientes muestran necesidades diferenciadas, con el fin de optimizar la oferta comercial y mejorar la experiencia del usuario.

Para ello, trabajarás con tres fuentes de datos:

plans.csv: los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra).
users_latam.csv: información de clientes: edad, ciudad, fecha de registro, plan contratado.
usage.csv: el detalle de uso real: llamadas (duración) y mensajes (longitud).
Tu misión será explorar, limpiar y analizar estas bases de datos para construir una visión clara, confiable y accionable sobre el comportamiento de uso de los clientes y cómo varía entre diferentes grupos de usuarios.

Objetivos de aprendizaje del proyecto
Al finalizar este proyecto, podrás:

Integrar y limpiar bases de datos provenientes de tres fuentes distintas.
Aplicar técnicas de validación, estandarización de tipos de datos y detección de valores inconsistentes.
Construir un perfil estadístico del uso (llamadas y mensajes) por cliente y por segmentos demográficos.
Detectar outliers y comportamientos atípicos mediante métodos estadísticos y visuales.
Crear segmentaciones de clientes basadas en edad, país y comportamiento de uso.
Visualizar diferencias entre segmentos y extraer insights comerciales relevantes.


🛠️ Herramientas de la lección
Jupyter Notebook
Python: pandas, numpy, seaborn, matplotlib
cómo ejecutar el notebook (por ejemplo, abrirlo en Google Colab),
una breve guía de reproducción.


Datasets del Proyecto
Trabajarás con tres fuentes principales de información, relacionadas con usuarios, actividad y planes del servicio de telecomunicaciones:

plans.csv: Catálogo de planes con sus precios y beneficios. Descárgalo aquí.(https://drive.google.com/uc?export=download&id=17Mkcs9rRWwiC_gaqVBYuFieON7s9v7Bn)

users_latam.csv: Información de cada usuario (datos personales, plan, fecha de registro, churn). Descárgalo aquí.
(https://drive.google.com/uc?export=download&id=17wuqxalUsUnw9PXvCN2_UaAz6xeS9B0T)

usage.csv: Actividad generada por los usuarios: llamadas, mensajes, duración, longitud. Descárgalo aquí.
(https://drive.google.com/uc?export=download&id=11T8MQf-ouxJu9tia4F8aNpY7M_fb9O4h)

Estos datasets se complementan para analizar el comportamiento del usuario, su consumo y cómo este se relaciona con el plan contratado, permitiendo detectar patrones de uso y churn.
