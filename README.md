
# Gestor de Tareas y Proyectos en Django

## 📖 Explicación del Proyecto
Esta aplicación web ha sido desarrollada como un sistema integral de gestión de proyectos y tareas personales. Su propósito principal es permitir a los usuarios registrarse de forma segura, organizar su trabajo diario mediante la creación de proyectos independientes y administrar las tareas asociadas a cada uno con distintos estados de avance. El sistema está construido utilizando Vistas Basadas en Clases (CBV) en Django, incorpora validaciones personalizadas en los formularios para asegurar la integridad de los datos, y cuenta con un diseño responsivo basado en Bootstrap 5.

---

## 🚀 Características Principales
- **Autenticación completa:** Registro de usuarios, inicio de sesión y control de sesiones personalizados.
- **Gestión de Proyectos:** Creación, listado y detalle de proyectos respaldados por validaciones personalizadas.
- **Control de Tareas:** Asociación directa de tareas a proyectos específicos con definición de estados.
- **Diseño Moderno y Responsivo:** Interfaz limpia adaptada con componentes profesionales de Bootstrap 5.

---

## 🛠️ Requisitos Previos y Dependencias
Antes de comenzar, asegúrate de tener instalado en tu equipo:
- Python (versión 3.14.6)
- pip (gestor de paquetes de Python)

Librerías principales requeridas:
- `Django`

---

## 📦 Instalación y Configuración

Sigue estos pasos para clonar el repositorio, configurar el entorno virtual y poner en marcha el proyecto en tu entorno local:

1. Clonar el repositorio:
   git clone <https://github.com/evelyn557/Django-web-app >
   cd Django-web-app

2. Crear el entorno virtual:
   - En Mac: python3 -m venv venv
   - En Windows: python -m venv venv

3. Activar el entorno virtual:
   - En Mac: source venv/bin/activate
   - En Windows: venv\Scripts\activate

4. Instalar las dependencias:
   pip install django

5. Aplicar las migraciones de la base de datos:
   python manage.py makemigrations
   python manage.py migrate

6. Crear un superusuario (opcional para el panel de administración):
   python manage.py createsuperuser

---

## 🖥️ Uso de la Aplicación

1. Ejecutar el servidor de desarrollo:
   python manage.py runserver
2. Abre tu navegador web e ingresa a la siguiente dirección: http://127.0.0.1:8000/
3. Regístrate con una cuenta nueva o inicia sesión para comenzar a gestionar tus proyectos y tareas.

---

## 🧪 Ejecución de Pruebas (Tests)

Para ejecutar la suite de pruebas unitarias y verificar el correcto funcionamiento lógico de la aplicación, utiliza el siguiente comando:
python manage.py test

---

## 📸 Evidencia de Funcionamiento (Capturas de Pantalla)

- Pantalla de Inicio de Sesión / Registro:
 <img width="1440" height="778" alt="inicio_sesión" src="https://github.com/user-attachments/assets/0652cb32-97c8-4e7e-a6c9-bdd3e21ed6f1" />


- Vista de Listado de Proyectos:
<img width="1436" height="775" alt="sitio_tareas" src="https://github.com/user-attachments/assets/3f44aa0f-b302-4d78-bcf8-bfa7a394851e" />
<img width="1435" height="775" alt="proyecto2" src="https://github.com/user-attachments/assets/876eb294-4dcc-4d4b-a3a4-08015e83931f" />
<img width="1437" height="777" alt="proyecto3" src="https://github.com/user-attachments/assets/6c2a4838-e8b2-442f-8bc2-e290210bbd07" />
<img width="1440" height="780" alt="proyecto4" src="https://github.com/user-attachments/assets/6842370d-8bbb-4a60-9493-761fdaebf0b5" />
<img width="1440" height="776" alt="proyecto5" src="https://github.com/user-attachments/assets/a630e417-def9-4886-87dc-6f932de75077" />
<img width="1440" height="557" alt="proyecto6" src="https://github.com/user-attachments/assets/54326d50-e2f5-4469-be5b-53637830822a" />

## 📸 Evidencia de Funcionamiento (videos)

- **Registro de Usuarios:**
  
 [Proyectos](assets/crear_usuario_nuevo.mov)


- **Creación proyecto App de Inventarios:**
  
  [Ver video](assets/proyectos.png)

- **Validación al crear usuario:**
  
  [Ver video](assets/validacion.mov)

- **Agregar tareas:**
  
  [Ver video](assets/agregar_tareas.mov)

- **Editar tareas:**
  
  [Ver video](assets/editar_tarea.mov) 

- **Eliminar proyectos:**
  
  [Ver video](assets/validacion.png)

- **Uso de panel de administración:**
  
  [Ver video](https://github.com/evelyn557/Django-web-app/raw/main/assets/panel_admin.mov)
  
  





