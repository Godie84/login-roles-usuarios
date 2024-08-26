# login-password-reset
Solución web para login de plataforma web, con gestion de usuarios, roles de usuarios, restablecimiento de contraseña por correo electrónico y control de sesiones

## Descripción

Este proyecto es una solución web login para el acceso a una plataforma con gestión de contraseñas vía correo electrónico, asignación de roles para los diferentes módulos de la plataforma.

## Características

- **Autenticacion**: Los empleados pueden solicitar permisos indicando el motivo, las fechas, y cualquier comentario adicional.
- **Gestión de contraseñas**: Los administradores pueden aprobar o rechazar solicitudes, así como revisar el historial de permisos.
- **Tipo de cifrado**: Hash MD5.

## Capturas de pantalla:

## LOGIN
![alt text](Login.png) 

## ADMINISTRADOR DE USUARIOS
![alt text](image-9.png) 

## REGISTRO DE USUARIOS
![alt text](image-11.png)

- **Diseño**: Las ventanas o cuadros de dialogo están basados en Modal.

## Tecnologías Utilizadas

- **Frontend**: HTML5, CSS3, JavaScript, BootStrap.
- **Backend**: PHP8
- **Base de Datos**: 10.4.28-MariaDB - mariadb.org binary distribution
- **Autenticación**: Basado en tokens
- **Servidor Web**: Apache/2.4.56 (Win64) OpenSSL/1.1.1t PHP/8.0.28
- **Version PHP**: Versión de PHP: 8.0.28
- **Notificaciones**: Email, SendMail
- **Versionamiento de Código**: Git

## Requisitos

- Versión de PHP: 8.0.28
- 10.4.28-MariaDB - mariadb.org
