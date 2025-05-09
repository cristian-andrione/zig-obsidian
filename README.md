# 🚀 Guía Completa: Aprender Zig en 2025 (Desde Cero hasta KubOS/CubeSats)

## 📅 Plan de Estructurado (1h/día, L-V)

### 🔰 Fase 1: Fundamentos (4 semanas)
- **Semana 1-2**: Sintaxis básica, tipos de datos, control de flujo  
  - [Zig Learn - Capítulo 1](https://ziglearn.org/chapter-1/)  
  - [Ejercicios en Ziglings](https://github.com/ratfactor/ziglings)  

- **Semana 3-4**: Memoria, punteros, structs  
  - [Documentación oficial de memoria](https://ziglang.org/documentation/master/#Memory)  

### ⚙️ Fase 2: Intermedio (6 semanas)
- **Semana 5-6**: Manejo de errores, testing  
  - [Zig Test Docs](https://ziglang.org/documentation/master/std/#std.testing)  

- **Semana 7-8**: Proyectos multiarchivo, build system  
  - [Zig Build System](https://ziglang.org/documentation/master/#Build-System)  

### 🛠️ Fase 3: Proyectos Prácticos (6 semanas)
- **Semana 9-10**: CLI Tool (calculadora/gestor de tareas)  
- **Semana 11-12**: Juego simple con Raylib  
  - [Raylib-Zig Bindings](https://github.com/ryupold/raylib.zig)  

### 🚀 Fase 4: KubOS y Sistemas Embebidos (8 semanas)
- **Semana 13-16**: Interacción con hardware (I2C/UART)  
  - [KubOS Hardware API](https://docs.kubos.com/latest/apis/hardware-api.html)  
- **Semana 17-20**: Driver para sensor en Zig + integración KubOS  

---

## 🛰️ Plataformas Alternativas a KubOS

| Plataforma    | Lenguaje | Compatibilidad con Zig  | Uso típico         |
| ------------- | -------- | ----------------------- | ------------------ |
| **FreeRTOS**  | C        | ✅ (via FFI)             | Microcontroladores |
| **NASA cFS**  | C        | ✅ (directa)             | Sistemas de vuelo  |
| **Zephyr OS** | C        | ✅ (módulos)             | IoT/Embebidos      |
| **ROS 2**     | C++      | ⚠️ (bindings complejos) | Robótica           |

---

## 🔥 Frameworks Destacados en Zig

### 🎮 Juegos
- [Mach Engine](https://machengine.org/) - Motor gráfico con Vulkan  
- [Zig-Gamedev](https://github.com/michal-z/zig-gamedev) - Ejemplos con DirectX/OpenGL  

### 🌐 Redes
- [HTTPZ](https://github.com/karlseguin/http.zig) - Servidor HTTP minimalista  
- [Zig-Net](https://github.com/MasterQ32/zig-network) - Sockets TCP/UDP  

### 🔌 Embebidos
- [Zig Embedded HAL](https://github.com/ziglang/zig/wiki/Embedded-development)  
- [Zig para ESP32](https://github.com/kubos/freeRTOS-zig)  

---

## 👨💻 Programadores y Proyectos Destacados

### Personajes clave
- **Andrew Kelley** ([@andrewrk](https://github.com/andrewrk)) - Creador de Zig  
- **Loris Cro** ([@kristoff_it](https://github.com/kristoff_it)) - TigerBeetle DB  
- **Jakub Konka** ([@kubkon](https://github.com/kubkon)) - Compilador LLVM  

### Proyectos notables
- [Bun.sh](https://bun.sh/) - Runtime JS con partes en Zig  
- [TigerBeetle](https://github.com/tigerbeetle/tigerbeetle) - DB financiera  
- [Zig Compiler](https://github.com/ziglang/zig) - Autohospedado en Zig  

---

## 📚 Recursos Adicionales

### Comunidad
- [Reddit r/Zig](https://www.reddit.com/r/Zig/)  
- [Discord Oficial](https://discord.gg/zig)  

### Aprendizaje
- [Awesome Zig](https://github.com/catdevnull/awesome-zig)  
- [Zig SHOWTIME](https://zig.show/) - Conferencias  

### Documentación
- [Referencia Oficial](https://ziglang.org/documentation/master/)  
- [Zig Std Lib](https://ziglang.org/documentation/master/std/)  

---

## 💡 Comparativa Zig vs Otros Lenguajes

| Característica      | Zig | C   | Rust |
| ------------------- | --- | --- | ---- |
| Seguridad memoria   | ✅   | ❌   | ✅    |
| Sin GC              | ✅   | ✅   | ✅    |
| Interop con C       | ⭐️  | ✅   | ⚠️   |
| Facilidad embebidos | ✅   | ✅   | ❌    |

---

