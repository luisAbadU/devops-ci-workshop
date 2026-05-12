#Correcciones
**Integrantes:**
- Nombre 1
- Nombre 2

## Error 1 
- **Archivo:** app.py
- **Problema:** La ruta estaba definida como /metric y en el resto de archivos la llamaba como /metrics.
- **Solución:** Cambiarla por /metrics, se cambio la ruta por la definida en el README 5000.

## Error 2
- **Archivo:** app.py
-- **Problema:** El endpoint no tenia el campo uptime_seconds
-- **Solución:** Agregar el campo, ademas de importar el time para restarlo con el boot_time y obtener los segundos

## Error 3
- **Archivo:** requirements.txt
-- **Problema:** Pytest no estaba definido en el requierements.txt
-- **Solucion:** Escribirlo

## Error 4
-- **Archivo:** app.py
-- **Problema:** El endpoint devolvía estatus running y el otro ok
-- **Solución:** Se dejó ambos en ok