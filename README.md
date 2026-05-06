# Nombre del Proyecto
Página Gimnasio  

## Descripción
Aplicación web en Django para gestión de gimnasio, venta de planes, administración de usuarios y creación/seguimiento de rutinas de ejercicio.  

## Instalación

### Requisitos
- Python 3.11  
- Virtualenv (recomendado)  

### Pasos sugeridos

1. Clona el repositorio o copia el proyecto a tu máquina.  

2. Navega al directorio del proyecto:

cd "c:\Users\crist\OneDrive\Documentos\Pagina-Gimnasio"

3. Crea y activa un entorno virtual:

python -m venv venv  
.\venv\Scripts\Activate.ps1  

4. Instala dependencias:

pip install -r requirements.txt  

5. Aplica migraciones:

django-admin migrate  

6. Crea un superusuario para acceder al admin:

django-admin createsuperuser  

## Uso

### Ejecución
Inicia el servidor de desarrollo:

django-admin runserver  

Luego abre en el navegador:  
http://127.0.0.1:8000/  

### Rutas principales
- / : página de presentación  
- /planes/ : listados de planes disponibles  
- /sobreNosotros/ : página sobre el gimnasio  
- /galeria/ : galería de imágenes  
- /comprar/<id_plan>/ : comprar un plan  
- /inicio/ : inicio de sesión o página principal después de login  
- /usuarios/login/ : login de usuario  
- /usuarios/logout/ : cerrar sesión  
- /rutinas/ : listado de rutinas  
- /rutinas/crear/ : crear rutina  
- /rutinas/<pk>/ : detalle de rutina  
- /rutinas/<pk>/editar/ : editar rutina  
- /rutinas/<pk>/eliminar/ : eliminar rutina  
- /rutinas/<pk>/iniciar/ : iniciar sesión de entrenamiento  
- /rutinas/sesion/<pk>/ : ejecutar rutina de entrenamiento  
- /rutinas/sesion/<pk>/finalizar/ : finalizar sesión  
- /rutinas/historial/ : historial de sesiones  

## Autores

Nombre | Código | Rol | Correo  
--- | --- | --- | ---  
Ana María Tique | 2220241069 | Front-end developer | ana.tique1@estudiantesunibague.edu.co  
Yaritxa Duarte | 2220241061 | Back-end developer | yaritxa.duarte@estudiantesunibague.edu.co  

## Flujo de trabajo Git

## Evidencias
