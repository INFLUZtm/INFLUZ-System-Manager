# INFLUZ™ SYSTEM MANAGER 

Herramienta de optimización para Windows 10/11, desarrollada por INFLUZ™.

## Requisitos

- Windows 10/11 (64-bit).
- Permisos de administrador.

## Perfiles Disponibles

### Gaming Seguro
**Lista de optimizaciones:**
- Deshabilitar animaciones de Windows
- Deshabilitar Game DVR
- Activar Game Mode
- Plan de energía: Alto Rendimiento

**Impacto**: +10-15% FPS

### Gaming Extremo
**Lista de optimizaciones:**
- Todo de Gaming Seguro +
- Deshabilitar transparencias
- Deshabilitar Aero Peek
- Efectos visuales mínimos

**Impacto**: +15-25% FPS

### Trabajo 💼
**Lista de optimizaciones:**
- Deshabilitar animaciones
- Plan de energía: Balanceado
- Optimización ligera
- Sin sacrificar estética

**Impacto**: Sistema más rápido y responsivo

## 🔧 Optimizaciones Incluidas

### V1 (Actual)
1. ✅ Deshabilitar animaciones de Windows
2. ✅ Deshabilitar Game DVR
3. ✅ Activar Game Mode
4. ✅ Plan de energía alto rendimiento/balanceado
5. ✅ Limpieza de archivos temporales
6. ✅ Crear punto de restauración

## 📝 Sistema de Logs

Todos los logs se guardan en la carpeta `logs/` con el formato:
```
influz_log_YYYYMMDD_HHMMSS.txt
```

Cada acción se registra con timestamp y resultado.

## 🔒 Seguridad

- **Punto de restauración automático** antes de cualquier cambio
- **No modifica**: Windows Defender, Windows Update, archivos del sistema
- **Reversible**: todas las optimizaciones pueden deshacerse desde Restaurar Sistema

## 🆘 Solución de Problemas

### "No se puede ejecutar el programa"
- Asegurarte de ejecutar como **administrador**

### "No se detecta la CPU/RAM"
- El programa usa WMIC (nativo de Windows)
- Si no funciona, verificar que Windows esté actualizado

### "Error al crear punto de restauración"
- Habilitar Protección del Sistema en Windows
- Panel de Control → Sistema → Protección del Sistema

## 📧 Soporte

Desarrollado por **INFLUZ™**
- Instagram: [@influz_](https://instagram.com/influz_)
- TikTok: [@influz_](https://tiktok.com/@influz_)

## 📄 Licencia

© 2026 INFLUZ™ - Todos los derechos reservados

---

**NOTA IMPORTANTE**: Este programa modifica configuraciones del sistema. Aunque es seguro, se recomienda:
1. Crear punto de restauración (lo hace automáticamente)
2. Leer las optimizaciones que se van a aplicar
3. Reiniciar después de optimizar
