# 🅰️ Guía Completa de Instalación de Angular

## 📋 Prerrequisitos Previos

### Verificar instalaciones necesarias
```bash
# Comprobar si Node.js está instalado
node --version

# Comprobar si npm está instalado  
npm --version
```

**⚠️ Requisitos mínimos:**
- Node.js versión 18 o superior
- npm versión 8 o superior

### Si no tienes Node.js instalado:
1. Ve a [nodejs.org](https://nodejs.org/)
2. Descarga la versión LTS (Recomendada)
3. Sigue el asistente de instalación

---

## 🚀 Instalación de Angular CLI

### Paso 1: Instalar Angular CLI globalmente
```bash
npm install -g @angular/cli
```

### Paso 2: Verificar la instalación
```bash
ng version
```

**✅ Deberías ver información sobre Angular CLI si la instalación fue exitosa.**

---

## 🆕 Crear tu Primer Proyecto Angular

### Paso 3: Navegar a donde quieres crear el proyecto
```bash
# Ejemplo: ir al escritorio
cd Desktop

# O crear una carpeta nueva
mkdir proyectos-angular
cd proyectos-angular
```

### Paso 4: Generar nuevo proyecto
```bash
ng new mi-primer-proyecto
```

**📝 Durante la creación te preguntará:**
```
? Would you like to add Angular routing? (y/N) 
? Which stylesheet format would you like to use? 
❯ CSS 
  SCSS   
  Sass   
  Less   
```

**Recomendación para principiantes:**
- Angular routing: **y** (Sí)
- Stylesheet format: **CSS**

### Paso 5: Navegar al proyecto creado
```bash
cd mi-primer-proyecto
```

---

## 🎯 Ejecutar la Aplicación

### Paso 6: Iniciar el servidor de desarrollo
```bash
ng serve
```

### Paso 7: Abrir en el navegador
Ve a: **[http://localhost:4200](http://localhost:4200)**

**✅ Deberías ver la página de bienvenida de Angular.**

---

## 🛠 Comandos Básicos que Debes Conocer

### Comandos de desarrollo
```bash
# Iniciar servidor de desarrollo
ng serve

# Compilar para producción
ng build

# Ejecutar pruebas
ng test
```

### Comandos para generar elementos
```bash
# Crear un nuevo componente
ng generate component nombre-componente

# Crear un servicio
ng generate service nombre-servicio

# Crear un módulo
ng generate module nombre-modulo
```

### Comandos abreviados
```bash
# En lugar de ng generate component
ng g c nombre-componente

# En lugar de ng generate service  
ng g s nombre-servicio
```

---

## 📁 Estructura de Carpetas del Proyecto

```
mi-primer-proyecto/
├── src/
│   ├── app/
│   │   ├── app.component.ts      # Componente principal
│   │   ├── app.component.html    # Vista del componente
│   │   └── app.module.ts         # Módulo principal
│   ├── assets/                   # Imágenes, fuentes, etc.
│   └── index.html               # Página principal
├── node_modules/                # Dependencias instaladas
├── package.json                # Configuración del proyecto
└── angular.json               # Configuración de Angular
```

---

## 🔧 Solución de Problemas Comunes

### Problema: Comando 'ng' no encontrado
**Solución:**
```bash
# Reinstalar Angular CLI
npm install -g @angular/cli

# Cerrar y reabrir la terminal
```

### Problema: Puerto 4200 está en uso
**Solución:**
```bash
# Usar un puerto diferente
ng serve --port 4201
```

### Problema: Error de permisos (macOS/Linux)
**Solución:**
```bash
# Ejecutar con permisos de administrador
sudo npm install -g @angular/cli
```

### Problema: Instalación muy lenta
**Solución:**
```bash
# Usar el registry de npm oficial
npm config set registry https://registry.npmjs.org/
```

---

## 💡 Consejos para Principiantes

### 1. **Mantén abierta la terminal**
El servidor se reinicia automáticamente cuando haces cambios.

### 2. **Usa un buen editor de código**
Recomendado: **Visual Studio Code** con la extensión **Angular Language Service**.

### 3. **Revisa la consola del navegador**
Presiona **F12** para ver errores y advertencias.

### 4. **Aprende los atajos de teclado**
- **Ctrl+C** en la terminal: Detener el servidor
- **Ctrl+S** en el editor: Guardar y ver cambios

---

## 🌐 Recursos de Aprendizaje

- **[Documentación Oficial](https://angular.io/docs)** - La mejor referencia
- **[Angular Tutorial](https://angular.io/tutorial)** - Tour de héroes (oficial)
- **[Angular CLI](https://cli.angular.io/)** - Referencia de comandos
- **[Stack Overflow](https://stackoverflow.com/questions/tagged/angular)** - Ayuda de la comunidad

---

## ✅ Checklist de Verificación

- [ ] Node.js instalado (versión 18+)
- [ ] npm instalado (versión 8+)
- [ ] Angular CLI instalado globalmente
- [ ] Proyecto creado exitosamente
- [ ] Servidor ejecutándose en localhost:4200
- [ ] Página de Angular visible en el navegador

---

## 🎉 ¡Felicidades!

Has instalado Angular correctamente. Ahora puedes comenzar a desarrollar aplicaciones web modernas.


*Última actualización: ${new Date().toLocaleDateString()}*  
*Versión de Angular: Consulta con `ng version`*
