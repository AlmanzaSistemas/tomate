# Conector SAP & HANA - Punto de Venta

Este programa se conecta con SAP y HANA para realizar diversas tareas en los siguientes módulos:

## Características

### Módulo Punto de Ventas
- Procesamiento de ventas en efectivo.
- Procesamiento de ventas con tarjeta.
- Procesamiento de ventas con QR.

### Módulo Almacén
- Gestión de traslados de stock.
- Monitoreo en tiempo real del inventario.

### Módulo Cambio de Precios
- Modificación de precios de productos de manera general.

## Requisitos

- SQL2019
- SQL ESTUDIO
- Crystal Reports
- SAP y HANA configurados correctamente.
- Visual Studio instalado.
- .NET Framework o .NET Core (según la versión usada en el proyecto).

## Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/AlmanzaSistemas/tomate.git
   ```
2. Abre el proyecto en Visual Studio.
3. Restaura las dependencias necesarias ejecutando en la Consola del Administrador de Paquetes:
   ```powershell
   dotnet restore
   ```
4. Si necesitas instalar manualmente las dependencias, usa:
   ```powershell
   Install-Package Sap.Data.Hana -Version 2.6.115
   Install-Package Microsoft.EntityFrameworkCore
   Install-Package Newtonsoft.Json
   ```

## Uso

1. Compila y ejecuta el proyecto en Visual Studio.
2. Configura la conexión a SAP HANA en el archivo de configuración.
3. Utiliza las funciones del programa según el módulo correspondiente.

## Contribución

Si deseas contribuir, sigue estos pasos:
1. Haz un fork del repositorio.
2. Crea una rama con tu nueva funcionalidad:
   ```bash
   git checkout -b nueva-funcionalidad
   ```
3. Realiza tus cambios y confirma los commits:
   ```bash
   git commit -m "Descripción del cambio"
   ```
4. Sube los cambios a tu fork:
   ```bash
   git push origin nueva-funcionalidad
   ```
5. Crea un pull request.

## Licencia

Indica la licencia del proyecto, por ejemplo:
```
MIT License
```

## Contacto

Si tienes preguntas o sugerencias, contáctame en [webmaster@almanza.com.bo](mailto:webmaster@almanza.com.bo).
