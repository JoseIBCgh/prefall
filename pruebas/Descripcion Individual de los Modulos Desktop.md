# AHRS
### Descripción general y propósito
Filtros Madgwick y Mahony
### Dependencias
No tiene
### Implementacion
- MadgwickAHRS.cs
- MAhonyAHRS.cs
# EKF
### Descripción general y propósito
Filtro EKF
### Dependencias
- ibcdatacsharp.UI.Common
- MathNet.Numerics.LinearAlgebra
### Implementacion
- EKF.cs
# Login
### Descripción general y propósito
Pantalla inicial de login
### Dependencias
- ibcdatacsharp.UI
- MySql.Data.MySqlClient
### Implementacion
- Connection.cs
- Dashboard.xaml
- Dashboard.xaml.cs
- LoginInfo.cs
# CamaraViewport
### Descripción general y propósito
Viewport de la camara
### Dependencias
- OpenCvSharp
- OpenCvSharp.WpfExtensions
### Implementacion
- CamaraViewport.xaml
- CamaraViewport.xaml.cs
# Commands
### Descripción general y propósito
Algunos comandos de la aplicacion
### Dependencias
- ibcdatacsharp.UI.Pacientes
- ibcdatacsharp.Login
### Implementacion
- SeleccionarPacienteCommand
- SubirTestCommand
# Common
### Descripción general y propósito
Funciones y clases de utilidad de la aplicación que se usan en varias partes
### Dependencias
No tiene
### Implementacion
- BaseObject.cs
- Helpers.cs
- PropertyNotifier.cs
# Device
### Descripción general y propósito
Sirve para generar datos aleatorios. (para testear)
### Dependencias
- ibcdatacsharp.UI.ToolBar.Enums
- ibcdatacsharp.UI.Timer
### Implementacion
- AngleArgs.cs
- Device.cs
- DeviceArgs.cs
- RawArgs
# DeviceList
### Descripción general y propósito
Componente de la lista de dispositivos (camaras y sensores)
### Dependencias
- ibcdatacsharp.DeviceList.TreeClasses
### Implementacion
- DeviceList.xaml
- DeviceList.xaml.cs
## DeviceList.Converters
### Descripción general y propósito
Sirve para adornar los datos a mostrar
### Dependencias
No tiene
### Implementacion
- BatteryConverter.cs
- ConnectedConverter.cs
- JAEnabledConverter.cs
## DeviceList.Enums
### Descripción general y propósito
Conjunto de enums que usa el paquete de la lista de dispositivos
### Dependencias
No tiene
### Implementacion
- Joint.cs
## DeviceList.TreeClasses
### Descripción general y propósito
Objetos que se muestran en la lista de dispositivos
### Dependencias
- ibcdatacsharp.Common
- ibcdatacsharp.UI.DeviceList.Enums
### Implementacion
- CameraInfo.cs
- DeviceListInfo.cs
- IMUInfo.cs
- InsolesInfo.cs
# FileBrowser
### Descripción general y propósito
Buscador de ficheros
### Dependencias
- ibcdatacsharp.Common
### Implementacion
- FileBrowser.xaml
- FileBrowser.xaml.cs
- FileManager.cs
- FolderManager.cs
- Interop.cs
- ShellManager.cs
## FileBrowser.Enums
### Descripción general y propósito
Conjunto de enums que usa el paquete FileBrowser
### Dependencias
No tiene
### Implementacion
- FileAttribute.cs
- IconSize.cs
- ItemState.cs
- ItemType.cs
- ShellAttribute.cs
## FileBrowser.ShellClasses
### Descripción general y propósito
Almacena todos los drives, carpetas y ficheros. Se encarga de la interacción entre el usuario y la UI.
### Dependencias
- ibcdatacsharp.Common
- ibcdatacsharp.UI.FileBrowser.Enums
### Implementacion
- DummyFileSystemObjectInfo.cs
- FileSystemObjectInfo.cs
## FileBrowser.ShellClasses
### Descripción general y propósito
Almacena la información extraida de la shell
### Dependencias
No tiene
### Implementacion
- ShellFileInfo.cs
# FileSaver
### Descripción general y propósito
Se encarga de manejar los buffers para guardar tanto el video como audio
### Dependencias
- ibcdatacsharp.UI.Device
- ibcdatacsharp.UI.ToolBar;
- ibcdatacsharp.UI.ToolBar.Enums;
- ibcdatacsharp.Login
- OpenCvSharp
- Newtonsoft.Json
### Implementacion
- DeviceList.xaml
- DeviceList.xaml.cs
# Filters
### Descripción general y propósito
Se encarga de escoger el filtro que se quiere usar.
### Dependencias
- AHRS
- ibcdatacsharp.UI.Common
- ibcdatacsharp.EKF.EKF
- WisewalkSDK
- MathNet.Numerics.LinearAlgebra
### Implementacion
- EKF.cs
- Filter.cs
- FilterManager.cs
- Madgwick.cs
- Mahoney.cs
- None.cs


