# Gestión de un Gimnasio
###### Sistema para administrar los miembros, sus pagos, clases y entrenadores, optimizando la organización y control de las actividades del gimnasio.
## Objetivos:
1. Facilitar la inscripción y gestión de nuevos miembros.
2. Automatizar el registro de pagos y control de membresías.
3. Administrar clases, entrenadores y asistencia de manera eficiente.
## Tecnologías a Utilizar:
- Python
- MySQL
- HTML, CSS y JavaScript

## Cita usando >:
> {!NOTE}
> "La disciplina es el puente entre tus metas y tus logros."

## Enlace:
[Enlace a Canva](https://www.canva.com)

## Imagen:
![Logo de Supabase](Grupo-2-Gimnasio-o-Club-Deportivo/Archivos/Supabase.jpg)

## Bloque de Código:
```python 
# Calcular el índice de masa corporal (IMC)
def calcular_imc(peso, altura):
    imc = peso / (altura ** 2)
    return round(imc, 2)

# Datos de ejemplo
peso = 70  # en kilogramos
altura = 1.75  # en metros

resultado = calcular_imc(peso, altura)
print(f"Tu índice de masa corporal es: {resultado}")