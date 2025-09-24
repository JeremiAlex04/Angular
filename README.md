# Guía de Instalación de Angular

## 📋 Prerrequisitos

Antes de comenzar, asegúrate de tener instalado:

- **Node.js** (versión 18 o superior)
- **npm** (generalmente viene incluido con Node.js)

### Verificar instalaciones previas
```bash
node --version
npm --version
```

## 🚀 Instalación Paso a Paso

### 1. Cambiar de unidad (Opcional)
Si deseas trabajar en otra unidad de disco:
```cmd
C:\Users\TuUsuario>d:
```

### 2. Crear carpeta de trabajo
```cmd
D:\>md SEMANA7
```

### 3. Navegar a la carpeta creada
```cmd
D:\>cd SEMANA7
```

### 4. Instalar Angular CLI globalmente
```cmd
D:\SEMANA7>npm install -g @angular/cli
```

### 5. Verificar la instalación
```cmd
D:\SEMANA7>ng version
```

### 6. Crear un nuevo proyecto
```cmd
D:\SEMANA7>ng new mi-proyecto-angular
```

**Nota:** Durante la creación, Angular te preguntará:
- ¿Quieres agregar Angular routing? (y/N)
- ¿Qué formato de stylesheet prefieres? (CSS, SCSS, etc.)

### 7. Navegar al directorio del proyecto
```cmd
D:\SEMANA7>cd mi-proyecto-angular
```

### 8. Iniciar el servidor de desarrollo
```cmd
D:\SEMANA7\mi-proyecto-angular>ng serve
```
O alternativamente:
```cmd
D:\SEMANA7\mi-proyecto-angular>npm start
```

### 9. Ver la aplicación
Abre tu navegador y visita: `http://localhost:4200`

## ✅ Verificación de la Instalación

Después de completar los pasos, deberías ver:

- **Terminal**: Mensaje "✔ Browser application bundle generation complete."
- **Navegador**: Página de bienvenida de Angular
- **Consola**: Sin errores críticos

## 🛠 Comandos Útiles

| Comando | Descripción |
|---------|-------------|
| `ng serve` | Inicia el servidor de desarrollo |
| `ng generate component nombre` | Crea un nuevo componente |
| `ng build` | Construye el proyecto para producción |
| `ng test` | Ejecuta las pruebas unitarias |
| `ng add [paquete]` | Añade una librería externa |

## ⚠️ Solución de Problemas Comunes

### Error: "ng no se reconoce como comando"
```bash
# Solución:
npm install -g @angular/cli
# Cerrar y reabrir la terminal
```

### Error de permisos (Windows)
- Ejecutar la terminal como Administrador

### Puerto 4200 en uso
```bash
ng serve --port 4201
```

### Limpiar cache de npm
```bash
npm cache clean --force
```

## 📁 Estructura del Proyecto

```
SEMANA7/
└── mi-proyecto-angular/
    ├── src/
    │   ├── app/
    │   ├── assets/
    │   └── environments/
    ├── node_modules/
    ├── package.json
    ├── angular.json
    └── tsconfig.json
```

## 🔄 Flujo de Desarrollo Típico

1. **Modificar código** en `src/app/`
2. **Guardar cambios** - el servidor se recarga automáticamente
3. **Ver resultados** en el navegador en tiempo real
4. **Probar funcionalidades** iterativamente

## 📝 Notas Importantes

- El servidor de desarrollo se recarga automáticamente con cada cambio
- Los archivos se compilan en memoria (no se crean archivos físicos en dist/)
- Usa `Ctrl + C` en la terminal para detener el servidor
- Recomendado: Usar Visual Studio Code con extensiones de Angular

## 🌐 Recursos Adicionales

- [Documentación Oficial de Angular](https://angular.io/docs)
- [Angular CLI Reference](https://angular.io/cli)
- [Angular en GitHub](https://github.com/angular/angular)

---

**¡Listo! Ahora tienes Angular instalado y funcionando correctamente.** 🎉
