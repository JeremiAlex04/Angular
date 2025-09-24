# Guía de Instalación de Angular

## Prerrequisitos
Antes de comenzar, asegúrate de tener instalado:
- **Node.js** (versión 18 o superior)
- **npm** (generalmente viene incluido con Node.js)

Puedes verificar las instalaciones con:
```bash
node --version
npm --version
```

## 📋 Pasos de Instalación
Ingresar a CMD (Simbolo de Sistema - Command Prompt)
### 1. Preparar el Entorno de Trabajo
Crea una carpeta para organizar tus proyectos de Angular:

```bash
# Cambiar a la unidad donde deseas trabajar (opcional)
d:

# Crear carpeta principal
mkdir proyectos-angular
cd proyectos-angular
```

### 2. Instalar Angular CLI Globalmente
```bash
npm install -g @angular/cli
```

### 3. Verificar la Instalación
```bash
ng version
```

### 4. Crear un Nuevo Proyecto
```bash
ng new mi-proyecto-angular
```

**Notas importantes durante la creación:**
- ✅ **Angular Routing**: Selecciona 'y' (yes) si quieres routing
- 🎨 **Stylesheet Format**: Elige el preprocesador CSS que prefieras (CSS, SCSS, Less, etc.)

### 5. Navegar al Directorio del Proyecto
```bash
cd mi-proyecto-angular
```

### 6. Ejecutar el Servidor de Desarrollo
```bash
ng serve
```

### 7. Visualizar la Aplicación
Abre tu navegador y visita: 
```
http://localhost:4200
```

## 🚀 Comandos Útiles

### Desarrollo
```bash
# Iniciar servidor de desarrollo
ng serve

# Compilar en modo producción
ng build --prod

# Ejecutar pruebas unitarias
ng test

# Ejecutar pruebas end-to-end
ng e2e
```

### Generadores de Código
```bash
# Generar un componente
ng generate component nombre-componente

# Generar un servicio
ng generate service nombre-servicio

# Generar un módulo
ng generate module nombre-modulo

# Generar una directiva
ng generate directive nombre-directiva
```

### Utilidades
```bash
# Actualizar Angular CLI globalmente
npm install -g @angular/cli@latest

# Actualizar dependencias del proyecto
ng update
```

## 🛠️ Solución de Problemas Comunes

### Error: "ng command not found"
```bash
# Cerrar y reabrir la terminal
# O ejecutar:
npm install -g @angular/cli
```

### Error de Permisos (Windows)
- Ejecutar la terminal como Administrador

### Error de Permisos (macOS/Linux)
```bash
sudo npm install -g @angular/cli
```

### Puerto 4200 en Uso
```bash
ng serve --port 4201
```

## 📁 Estructura del Proyecto
```
mi-proyecto-angular/
├── src/
│   ├── app/
│   │   ├── components/
│   │   ├── services/
│   │   ├── models/
│   │   └── app.module.ts
│   ├── assets/
│   ├── environments/
│   └── index.html
├── node_modules/
├── package.json
└── angular.json
```

## ✅ Verificación Final
Después de la instalación, verifica que todo funcione correctamente:

1. ✅ Angular CLI instalado: `ng version`
2. ✅ Proyecto creado: `cd mi-proyecto-angular`
3. ✅ Servidor ejecutándose: `ng serve`
4. ✅ Aplicación visible en: `http://localhost:4200`

## 📚 Recursos Adicionales
- [Documentación Oficial de Angular](https://angular.io/docs)
- [Angular CLI Reference](https://angular.io/cli)
- [Angular Style Guide](https://angular.io/guide/styleguide)

---

**¡Listo! Ahora tienes Angular instalado y funcionando. 🎉**
