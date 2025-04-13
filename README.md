# Sistema de Gestión de Usuarios y Productos

## Descripción
Este proyecto es un sistema de gestión desarrollado en Java que permite administrar usuarios, productos y realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) sobre una base de datos Access.

## Desarrolladores
- [Wilmer Zuniga](https://github.com/wilzuniga)
- [Kevin Banegas](https://github.com/KevinBanegasUNITEC)

## Características Principales
- Gestión de usuarios (creación, modificación, eliminación y listado)
- Interfaz gráfica intuitiva desarrollada con Java Swing
- Integración con base de datos Access
- Sistema de autenticación de usuarios
- Gestión de productos y tiendas
- Funcionalidades de administrador

## Estructura del Proyecto
```
src/
├── proyectofinal/        # Código principal de la aplicación
├── Clases/              # Clases base del sistema
├── Correo/              # Funcionalidades de correo
├── DataBase/            # Conexión y operaciones con la base de datos
└── Imagenes/            # Recursos gráficos
```

## Requisitos del Sistema
- Java JDK 8 o superior
- Microsoft Access
- UCanAccess (para conexión con Access)
- NetBeans IDE (recomendado para desarrollo)

## Configuración
1. Clonar el repositorio:
   ```bash
   git clone [URL del repositorio]
   ```

2. Importar el proyecto en NetBeans IDE

3. Configurar la base de datos:
   - Asegurarse de que el archivo `DatosPrograma.accdb` esté en la raíz del proyecto
   - Verificar la conexión en la clase `DbCon`

4. Compilar y ejecutar el proyecto

## Uso
1. Iniciar la aplicación
2. Iniciar sesión con credenciales de administrador
3. Navegar por el menú principal para acceder a las diferentes funcionalidades:
   - Gestión de usuarios
   - Gestión de productos
   - Gestión de tiendas
   - Reportes y listados

## Contribución
1. Fork el proyecto
2. Crear una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abrir un Pull Request

## Licencia
Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## Contacto
Para cualquier consulta o sugerencia, por favor contactar a los desarrolladores del proyecto:
- Wilmer Zuniga: [GitHub](https://github.com/wilzuniga)
- Kevin Banegas: [GitHub](https://github.com/KevinBanegasUNITEC) 
