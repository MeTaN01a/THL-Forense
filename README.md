# Operación BlueMoon
<img width="1536" height="1024" alt="BlueMoon" src="https://github.com/user-attachments/assets/213bb6f2-b939-4502-8435-ebb9eebe398c" />

Trabajas como analista en un Centro de Operaciones de Seguridad (SOC).
Alguien contacta a tu equipo para informar que un compañero de trabajo ha descargado un archivo sospechoso después de buscar Google Authenticator. 
La persona que llama proporciona información similar a las publicaciones en redes sociales en:

•	https://www.linkedin.com/posts/unit42_2025-01-22-miércoles-actividad-generada-por-anuncios-maliciosos-7288213662329192450-ky3V/

•	https://x.com/Unit42_Intel/status/1882448037030584611

Basándose en la información inicial de la persona que llama, confirma que hubo una infección. Recupera una captura de paquetes (pcap) del tráfico asociado. 
Al revisar el tráfico, encuentra varios indicadores que coinciden con los detalles de una página de Github a la que hace referencia en las publicaciones de redes sociales anteriores. 
Después de confirmar que se produjo una infección, comienza a escribir un informe de incidentes.

<img width="920" height="476" alt="image" src="https://github.com/user-attachments/assets/99d1b554-9fa7-4cfd-8bc7-600c39de0281" />

El Pcap
<img width="919" height="424" alt="image" src="https://github.com/user-attachments/assets/f2a957ef-ae6f-4139-982a-17abf75dfc96" />

Una vez detectado aislamos las líneas que contienen la información
<img width="920" height="198" alt="image" src="https://github.com/user-attachments/assets/f6f10a6c-9518-45bb-a282-a672c84d4b6e" />

Para este ejercicio, responda las siguientes preguntas para completar el LAB.

•	¿Cuál es la dirección IP del cliente de Windows infectado?

Respuesta: 10.1.17.215
<img width="919" height="274" alt="image" src="https://github.com/user-attachments/assets/0b88a0b8-3cb0-4018-9e09-de27ef9ec1ba" />

•	¿Cuál es la dirección MAC del cliente de Windows infectado?

Respuesta: 00:d0:b7:26:4a:74
<img width="919" height="386" alt="image" src="https://github.com/user-attachments/assets/0cb0a013-23c3-4302-9a9b-ed286f27a5b4" />

•	¿Cuál es el nombre de host del cliente de Windows infectado?

Respuesta: DESKTOP-L8C5GSJ
<img width="920" height="456" alt="image" src="https://github.com/user-attachments/assets/58e486be-5d35-4fa9-9038-5c9754c86279" />

•	¿Cuál es el probable nombre de dominio de la página falsa de Google Authenticator?

Respuesta: client.wns.windows.com
<img width="919" height="445" alt="image" src="https://github.com/user-attachments/assets/9bf7421a-59c0-40a9-ae76-aac102861248" />

Confirmamos nuevamente la IP del cliente infectado: 10.1.17.215
Muestra el destino legitimo: 20.10.31.115 IP de Microsoft (servicio windows)

•	¿Cuál es el posible sitio de software falso para la descarga inicial del malware?

Respuesta: authenticatoor.org
<img width="831" height="258" alt="image" src="https://github.com/user-attachments/assets/a4802280-43b5-49c5-adb3-82e1a6d46abe" />
<img width="920" height="286" alt="image" src="https://github.com/user-attachments/assets/aa87099f-d18f-4838-abb9-2495315da228" />

•	¿Cuál es el nombre de la cuenta de usuario del cliente de Windows infectado?

Respuesta: shutchenson
<img width="919" height="441" alt="image" src="https://github.com/user-attachments/assets/9103f166-5310-4c8a-979a-865eb8098069" />
