# Factu_Easy_Pro 📊

![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

Un Sistema de Gestión Empresarial (ERP) moderno y eficiente, diseñado para simplificar y automatizar las operaciones clave de pequeñas y medianas empresas.

---

## 📜 Acerca del Proyecto

**Factu_Easy_Pro** es una aplicación web full-stack desarrollada con **Django** y **Python** que ofrece una solución integral para la gestión de facturación, inventario, clientes y proveedores. El objetivo principal de este proyecto es centralizar la información crítica del negocio en una plataforma intuitiva, segura y escalable.

Este repositorio documenta la **primera fase de desarrollo** y sirve como un portafolio para demostrar las habilidades en el diseño de arquitectura de software, desarrollo backend y frontend, y modelado de bases de datos.

## ✨ Características Principales

El sistema está organizado en módulos interconectados para cubrir todas las áreas de gestión de una empresa:

#### 📂 **Datos Generales y Configuración**
- **Gestión de Empresas:** Registro de múltiples empresas o sucursales.
- **Configuraciones Regionales:** Administración de estados, ciudades y divisas.
- **Configuración Fiscal:** Manejo de tipos de documentos, impuestos y secuenciales.
- **Parámetros del Sistema:** Formas de pago, licencias y más.

#### 🛒 **Módulo de Compras**
- **Gestión de Proveedores:** Base de datos completa de proveedores.
- **Documentos de Compra:** Registro y seguimiento de órdenes de compra y facturas.
- **Ajustes de Costos:** Herramientas para actualizar costos de productos.

#### 📈 **Módulo de Ventas**
- **Gestión de Clientes:** Ficha completa del cliente y su historial.
- **Facturación:** Creación, emisión y seguimiento de facturas de venta.
- **Punto de Venta (POS):** Interfaz optimizada para ventas rápidas en mostrador.
- **Presupuestos:** Generación y gestión de cotizaciones para clientes.

#### 📦 **Gestión de Productos e Inventario**
- **Catálogo Detallado:** Creación de artículos con múltiples atributos (categoría, marca, talla, color, etc.).
- **Control de Almacenes:** Gestión de múltiples bodegas o almacenes.
- **Movimientos de Inventario:** Trazabilidad completa de entradas, salidas y transferencias.
- **Alertas de Stock:** Notificaciones automáticas para niveles bajos de inventario.

#### ⚙️ **Administración y Seguridad**
- **Gestión de Usuarios y Permisos:** Roles personalizables para controlar el acceso a cada módulo.
- **Auditoría de Acciones:** Registro de las operaciones importantes realizadas en el sistema.
- **Copias de Seguridad (Backup):** Funcionalidad para resguardar y restaurar la base de datos.

---

## 🖼️ Galería de la Aplicación

Una vista previa de la interfaz de usuario y las funcionalidades clave del sistema.

| Formulario de Empresa | Listado y Acciones | Menús de Navegación |
| :---: | :---: | :---: |
| ![Formulario de Datos de la Empresa](URL_A_TU_IMAGEN_1) | ![Listado de Empresas Registradas](URL_A_TU_IMAGEN_2) | ![Menús del Sistema](URL_A_TUS_IMAGENES_DE_MENU) |

*(**Nota para ti:** Para que esto funcione, crea una carpeta en tu repositorio, por ejemplo, llamada `.github/images/`, sube tus capturas de pantalla allí y reemplaza `URL_A_TU_IMAGEN_...` con el enlace directo a cada imagen en GitHub).*

---

## 🛠️ Tecnologías Utilizadas

- **Backend:** Python, Django Framework
- **Frontend:** HTML5, CSS3, JavaScript
- **Base de Datos:** SQLite (para desarrollo), adaptable a PostgreSQL/MySQL (para producción)
- **Servidor de Desarrollo:** Django Development Server

---

## 🚀 Instalación y Puesta en Marcha

Si deseas ejecutar este proyecto en un entorno local, sigue estos pasos:

<details>
<summary><strong>Haz clic aquí para ver las instrucciones de instalación</strong></summary>

1.  **Clona el repositorio:**
    ```bash
    git clone https://github.com/tu-usuario/Factu_Easy_Pro.git
    cd Factu_Easy_Pro
    ```

2.  **Crea y activa un entorno virtual:**
    ```bash
    # Para Windows
    python -m venv venv
    .\venv\Scripts\activate

    # Para macOS/Linux
    python3 -m venv venv
    source venv/bin/activate
    ```

3.  **Instala las dependencias:**
    *(Asegúrate de tener un archivo `requirements.txt` en tu repositorio)*
    ```bash
    pip install -r requirements.txt
    ```

4.  **Realiza las migraciones de la base de datos:**
    ```bash
    python manage.py migrate
    ```

5.  **Crea un superusuario para acceder al panel de administración:**
    ```bash
    python manage.py createsuperuser
    ```

6.  **Ejecuta el servidor de desarrollo:**
    ```bash
    python manage.py runserver
    ```

7.  Abre tu navegador y ve a `http://127.0.0.1:8000` para ver la aplicación.

</details>

---

## 🗺️ Roadmap y Futuras Mejoras

Esta es la primera fase del proyecto. Los siguientes pasos planeados incluyen:

- [ ] **Dashboard Principal:** Un panel de control con métricas y gráficos clave (ventas del día, top productos, etc.).
- [ ] **Integración de API de Facturación Electrónica:** Conectar con servicios fiscales locales.
- [ ] **Mejoras en la UI/UX:** Refinar el diseño y la experiencia de usuario.
- [ ] **Despliegue a Producción:** Contenerizar la aplicación con Docker y desplegarla en un servicio en la nube.
- [ ] **Pruebas Unitarias:** Implementar una suite de tests para garantizar la estabilidad del código.

---

## 🧑‍💻 Desarrolladores

- **Rafael Soto**
- **Dulimar Pire**

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.
