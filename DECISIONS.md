# DECISIONS

## 2026-10-15

### Decisión

Crear la estructura inicial de la base de datos en memoria.

### Justificación

El dominio Clínica Veterinaria requiere almacenar información de mascotas y vacunas.

### Implementación

```python
base_datos = {
    "mascotas": {},
    "vacunas": {}
}
```

### Beneficio

Permite preparar el sistema para las siguientes funcionalidades del proyecto.

### Nueva decisión

Agregar documentación inicial al módulo veterinaria.py.

### Justificación del cambio

Pylint reportó el aviso C0114 indicando que el módulo
no contaba con documentación inicial.

### Implementación aplicada

```python
"""
Proyecto Integrador: Clínica Veterinaria.

Inicialización de la base de datos en memoria.
"""
