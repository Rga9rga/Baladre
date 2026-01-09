<div align="center">
  <img src="public/assets/logo-baladre.png" alt="Baladre Logo" width="200" />

  # 🎲 B A L A D R E

  **El juego de dados que no sabías que necesitabas (y probablemente sigas sin necesitar).**

  [![PHP Version](https://img.shields.io/badge/php-%5E8.2-777BB4?style=for-the-badge&logo=php&logoColor=white)](https://www.php.net/)
  [![Laravel](https://img.shields.io/badge/laravel-%23FF2D20.svg?style=for-the-badge&logo=laravel&logoColor=white)](https://laravel.com)
  [![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com)
  [![Livewire](https://img.shields.io/badge/livewire-%234e56a6.svg?style=for-the-badge&logo=livewire&logoColor=white)](https://livewire.laravel.com)

  <p>
    <a href="#-sobre-el-proyecto">Sobre el Proyecto</a> •
    <a href="#-mecánicas">Mecánicas</a> •
    <a href="#-instalación">Instalación</a> •
    <a href="#-equipo">El Equipo</a>
  </p>
</div>

---

## 🔮 Sobre el Proyecto

**Baladre** es nuestro Proyecto Final de Ciclo (DAW). Es una reinterpretación "vitaminada" y basada en dados del exitoso *Balatro*.

El objetivo es simple: conseguir puntos haciendo jugadas de póker con dados (parejas, fulls, escaleras) para superar ciegas cada vez más absurdas. Todo ello envuelto en una estética **Cyber-Neón** oscura y minimalista.

> **Nota:** No es un casino, no apostamos dinero real. La única divisa aquí son los "Baladrones" y tu estabilidad mental intentando sacar un Repóker.

### 📸 Capturas (Próximamente)

| Login Psicodélico | Tablero de Juego | La Tienda |
|:---:|:---:|:---:|
| ** | ** | ** |

---

## ⚡ Características Principales

* **Sistema de Cuentas:** Registro, login, recuperación de contraseña y perfiles de usuario con avatares.
* **Gameplay Reactivo:** * Tiradas de dados con físicas (bueno, animaciones CSS/JS chulas).
    * Sistema de **Bloqueo (Lock)** y **Reroll**.
    * Detección automática de manos (Full, Escalera, etc.).
* **Progresión Roguelike:**
    * 6 Ciegas, 3 niveles cada una (18 rondas de sufrimiento).
    * Tienda de mejoras permanentes: Compra más rerolls o bloqueos usando **Baladrones**.
* **Estética:** Modo oscuro obligatorio. Paleta de colores restringida (🔴 Rojo, 🔵 Azul, 🟡 Amarillo) sobre negro profundo.

---

## 🛠️ Stack Tecnológico

Hemos decidido simular un entorno de desarrollo moderno y ágil, alejándonos de SPAs complejas innecesarias para este caso de uso:

* **Backend:** Laravel 10/11 (PHP).
* **Frontend & Reactividad:** Laravel Livewire 3 (Lógica de servidor en tiempo real).
* **Estilos:** Tailwind CSS.
* **Base de Datos:** MySQL / MariaDB.

---

## 🚀 Instalación y Despliegue

¿Quieres probar Baladre en local? Sigue estos pasos y reza para que no falte ninguna dependencia.

1.  **Clonar el repositorio**
    ```bash
    git clone [https://github.com/tu-usuario/baladre.git](https://github.com/tu-usuario/baladre.git)
    cd baladre
    ```

2.  **Instalar dependencias de PHP y Node**
    ```bash
    composer install
    npm install && npm run build
    ```

3.  **Configurar entorno**
    ```bash
    cp .env.example .env
    php artisan key:generate
    ```
    *Configura tu base de datos en el archivo `.env`.*

4.  **Migraciones (Crear las tablas)**
    ```bash
    php artisan migrate --seed
    ```

5.  **Lanzar**
    ```bash
    php artisan serve
    ```

---

## 💀 El Equipo (Los Culpables)

Este proyecto ha sido desarrollado con amor, estrés y mucho código por:

* 💻 **Rubén Gálvez** - *Full Stack Developer & Domador de CSS*
* 🎨 **Álvaro García** - *Frontend Architect & Animaciones*
* ⚙️ **Iker Muñoz** - *Backend Logic & Database Master*

---

<div align="center">
    <sub>Proyecto realizado para el ciclo de Desarrollo de Aplicaciones Web (DAW) - 2025/2026</sub>
</div>
