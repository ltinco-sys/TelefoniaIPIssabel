# TelefoniaIPIssabel

**Aplicación de la telefonía IP Issabel para fomentar la comunicación entre las áreas en la empresa Teleperformance.**

Proyecto académico desarrollado en el curso de Redes y Comunicaciones I.

## Descripción del proyecto

TelefoniaIPIssabel es un proyecto que documenta la implementación y configuración de una central de telefonía IP utilizando Issabel PBX, con el propósito de mejorar la comunicación interna entre las diferentes áreas de una organización.

La solución utiliza tecnología VoIP para gestionar llamadas internas mediante extensiones SIP, menús de respuesta interactiva (IVR) y colas de espera. También incorpora herramientas para la administración y seguimiento de las comunicaciones.

El proyecto contempla la configuración del servidor Issabel, la integración de Zoiper como cliente de telefonía y las pruebas de funcionamiento de los servicios implementados.

## Funcionalidades implementadas

- **Extensiones SIP:** creación y configuración de extensiones para las diferentes áreas.
- **Sistema IVR:** configuración de menús interactivos para dirigir las llamadas.
- **Colas de espera:** distribución de llamadas según la disponibilidad de las extensiones.
- **Grabaciones del sistema:** incorporación de mensajes de audio para los menús IVR.
- **Música en espera:** reproducción de audio durante la espera de llamadas.
- **Administración de usuarios y roles:** configuración de diferentes niveles de acceso.
- **Funciones adicionales:** grabación de llamadas, buzón de voz, reportes CDR y respaldo del sistema.
- **Integración con Zoiper:** registro de extensiones y realización de llamadas entre usuarios.

## Tecnologías y herramientas utilizadas

| Tecnología / herramienta | Descripción |
|---|---|
| Issabel PBX | Plataforma de central telefónica IP. |
| Asterisk | Motor de comunicaciones utilizado por Issabel. |
| VoIP | Tecnología para transmitir voz mediante redes IP. |
| SIP | Protocolo de señalización para las extensiones telefónicas. |
| Zoiper | Cliente de telefonía IP para realizar llamadas. |
| Oracle VM VirtualBox | Software de virtualización para ejecutar el servidor. |
| MariaDB | Sistema de gestión de bases de datos utilizado por la plataforma. |

## Descarga de la máquina virtual

La máquina virtual utilizada para la implementación se encuentra alojada en Google Drive.

- **Archivo:** `IssabelTeleperformance.ova`
- **Formato:** OVA (Open Virtualization Appliance).
- **Tamaño:** 2.43 GB.
- **Plataforma:** Oracle VM VirtualBox.

[Descargar máquina virtual IssabelTeleperformance](https://drive.google.com/drive/folders/11yBe37RbWcQ9-45k-9o2DGejpzDd8zob?usp=drive_link)

## Requisitos previos

Para utilizar la implementación se requiere:

- Oracle VM VirtualBox instalado.
- Archivo de máquina virtual `IssabelTeleperformance.ova`.
- Equipo con recursos suficientes para ejecutar la máquina virtual.
- Cliente Zoiper para registrar las extensiones SIP.
- Conectividad de red entre el servidor Issabel y los clientes.

## Instalación y ejecución

1. Instalar Oracle VM VirtualBox en el equipo.
2. Descargar el archivo `IssabelTeleperformance.ova` desde el enlace proporcionado.
3. Abrir VirtualBox y seleccionar **Archivo → Importar servicio virtualizado**.
4. Seleccionar el archivo OVA descargado y completar el proceso de importación.
5. Iniciar la máquina virtual y verificar el funcionamiento del servidor Issabel.
6. Acceder al panel web de Issabel mediante la dirección IP asignada al servidor.
7. Configurar Zoiper con los datos de las extensiones SIP correspondientes para realizar las pruebas de comunicación.

Para conocer el procedimiento detallado de instalación y configuración, consulta el manual de implementación.

## Documentación del proyecto

Los documentos que acompañan el proyecto se encuentran en la carpeta `docs/`:

- **Artículo académico:** presenta el desarrollo del proyecto, la metodología aplicada, los resultados obtenidos y las conclusiones.
- **Manual de implementación:** contiene el procedimiento de instalación y configuración de Issabel PBX, creación de extensiones, configuración de IVR, colas de espera e integración con Zoiper.
