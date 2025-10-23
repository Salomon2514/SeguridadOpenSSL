
## ![Seguridad](https://img.shields.io/badge/Código-Seguro-green?style=flat&logo=github&logoColor=white) Seguridad con OpenSSL en PHP
OpenSSL es una biblioteca criptográfica que permite una implementación de código abierto de los protocolos de seguridad de la capa de transporte (TLS) y capa de sockets seguros (SSL). Proporciona funciones para generar claves privadas, administrar certificados y equipar aplicaciones cliente con cifrado y descifrado.

## 🌐 Tecnologías utilizadas  

![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white) 
![Apache](https://img.shields.io/badge/Apache-D22128?style=for-the-badge&logo=apache&logoColor=white) 
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white) 
![XAMPP](https://img.shields.io/badge/XAMPP-F37623?style=for-the-badge&logo=xampp&logoColor=white) 
![WampServer](https://img.shields.io/badge/WampServer-FF0040?style=for-the-badge&logo=windows&logoColor=white)


### Los Algoritmos de Generación de clave más utlilizados y soportados son RSA, DSA y ECDSA
Los algoritmos de generación de clave más utilizados y soportados son RSA, DSA y ECDSA.

### Aplicaciones de OpenSSL en Ciberseguridad 
OpenSSL se utiliza ampliamente en el campo de la ciberseguridad para una amplia gama de aplicaciones, entre las que se incluyen:

1. Seguridad del servidor web: OpenSSL se utiliza comúnmente para habilitar HTTPS (HTTP sobre SSL/TLS) en servidores web, proporcionando cifrado y autenticación para una comunicación segura entre clientes y servidores.<br>

2. Seguridad del correo electrónico: OpenSSL se utiliza para proteger las comunicaciones de correo electrónico, permitiendo el uso de S/MIME (Secure/Multipurpose Internet Mail Extensions) y PGP (Pretty Good Privacy) para el cifrado de correo electrónico y firmas digitales.



### Configuración
1. Instalar en la raíz C.(Evitar espacios en blanco)
2. En la  versión de Xampp, verificar que tenga habilitada la extensión de extension=openssl
   El php.ini deben abrirlo con WordPad o Bloc de Notas y buscar la línea ;extension=openssl --> si tiene ";" eliminarlo y bajar los servicios y luego levantarlos  
3. Bajar la Versión Exe.
4. En algunos ejemlos deben asegurarse de establecer la ruta dónde instalarón el OpenSSL --> openssl.cnf (Ubicación de OpenSSL en su PC)
Ejemplo:

```bash
   $configArgs = array(
    'config' => 'C:\OpenSSL-Win64\bin\cnf\openssl.cnf', //<-- esta ruta es necesaria si trabajas con XAMPP
    'private_key_bits' => 2048,
    'private_key_type' => OPENSSL_KEYTYPE_RSA ); 
```


### Ejecutar los siguienstes ejemplos
1. Encriptacion.php
2. FirmaMensaje.php
3. Firma7.php
4. FirmaOtra.php

**Editor de Código :** 
- Visual Estudio Code

## 🔢 Estadísticas

 ![Creado](https://img.shields.io/badge/Creado-08--04--2025-blue)
![Visitor Count](https://badgen.net/github/watchers/Salomon2514/SeguridadOpenSSL)
![Visitas](https://visitor-badge.laobi.icu/badge?page_id=Salomon2514.SeguridadOpenSSL)

## 📚 Cómo usar este repositorio

1. Descarga o clona el repositorio, ubica una carpeta en www -> para WampServer o htdocs  si es Xampp
  ```bash
   [https://github.com/Salomon2514/SeguridadOpenSSL.git]
2. Para correrlos edita el URL de su navegador:  http://127.1.1.1/Carpeta/ o  http://localhost/Carpeta/
```

## 👨‍🏫 Autor

**Irina Fong**  
Docente de Programación  
Universidad Tecnológica de Panamá  

📧 **Email:** irina.fong@utp.ac.pa  
📧 **Email:** irinafong@gmail.com<br>
🌐 **GitHub:**(https://github.com/Salomon2514)  


## 📖 Referencias

- [https://www.youtube.com/watch?v=cBa87N_BZ4s&t=40s]
- [https://slproweb.com/products/Win32OpenSSL.html]



