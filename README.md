# 💰 Sistema de Préstamos — Laravel

Sistema completo de gestión de préstamos desarrollado con **Laravel + Blade**, diseñado para administrar clientes, agentes, supervisores y operaciones financieras de forma eficiente.

---

## 🚀 Características principales

- 🔐 Gestión de roles de usuario:
  - Administrador
  - Supervisor
  - Agente
  - Cliente
- 💵 Administración de préstamos con intereses y cuotas
- 🏦 Control de bóvedas y asignación de fondos
- 📍 Rutas de cobro para agentes
- 📊 Estadísticas por agente
- 📈 Reportes financieros y de gastos
- 📜 Historial de pagos
- 🔄 Cierre de rutas
- 👤 Gestión de perfiles de clientes

---

## 🌐 Demo

🔗 https://sistema-prestamos-youtube.herokuapp.com/login  

> ⚠️ Nota: Los datos del sistema demo se reinician automáticamente cada 60 minutos.

---

## ▶️ Instalación en video

📺 https://www.youtube.com/watch?v=g1KBAwJ8r4k

---

## 🧑‍💼 Roles del sistema

### 👤 Cliente
Persona que solicita un préstamo y puede pagar en múltiples cuotas con interés definido.

---

### 🚶 Agente
Encargado de:
- Captar clientes  
- Registrar pagos  
- Ejecutar rutas de cobro  

---

### 🧑‍💼 Supervisor
Responsable de:
- Gestionar una bóveda  
- Asignar fondos a agentes  
- Supervisar operaciones  

---

### 🛠️ Administrador
Control total del sistema:
- Crear usuarios  
- Gestionar bóvedas  
- Supervisar todos los módulos  

---

## 🧱 Tecnologías utilizadas

- **Laravel**
- **PHP**
- **Blade**
- **MySQL**
- **Bootstrap**
- **JavaScript**

---

## ⚙️ Requisitos


- PHP >= 5.6.4
- Composer
- MySQL o MariaDB
- Servidor local (XAMPP, Laragon, etc.)

---

## 🛠️ Instalación

# Clonar repositorio
```
git clone https://github.com/tu-usuario/sistema-prestamos.git
```
# Entrar al proyecto
```
cd sistema-prestamos
```
# Instalar dependencias
```
composer install
```
# Configurar entorno
```
cp .env.example .env
```
# Generar clave
```
php artisan key:generate
```
# Migraciones
```
php artisan migrate
```
# Seeders
```
php artisan db:seed
```
# Ejecutar servidor
```
php artisan serve
```

---

## ⚙️ Configuración adicional

### 🕒 Zona horaria

Editar en:
```
config/app.php
'timezone' => 'America/Mexico_City',
```
---

## 🚀 Producción

En el archivo .env:
```
APP_ENV=production
APP_DEBUG=false
```

---

## 🔑 Usuarios de prueba

Después de ejecutar migraciones y seeders:

R| Rol        | Usuario                    | Contraseña |
|------------|----------------------------|------------|
| Admin      | admin@admin.com            | 12345678   |
| Supervisor | supervisor@supervisor.com  | 12345678   |
| Agente     | agente@agente.com          | 12345678   |

---

## 🤝 Contribuciones

- Haz un fork del repositorio
- Crea una rama (feature/nueva-funcionalidad)
- Realiza tus cambios
- Envía un Pull Request

---

## 👨‍💻 Autor

**Isai Reyes**

---

## 📄 Licencia

Licence Mit
