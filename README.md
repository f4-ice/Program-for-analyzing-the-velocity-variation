# Análisis de Velocidad mediante Cálculo Integral

Este proyecto es un simulador interactivo construido en Python usando [Streamlit](https://streamlit.io/) que analiza el movimiento de un vehículo aplicando la **Segunda Ley de Newton** y los principios del **Cálculo Integral**.

## Características

- Configuración de parámetros físicos (masa del vehículo, fuerza del motor, fuerza de resistencia y velocidad inicial).
- Cálculo de la velocidad en el tiempo mediante la integración numérica de la aceleración neta.
- Gráficos interactivos que visualizan la relación cinemática, demostrando cómo la velocidad equivale al área bajo la curva de la aceleración.
- Registros detallados de integración paso a paso en formato de tabla.

## Requisitos

Asegúrate de tener instalado Python. Las librerías principales de este proyecto son:

- `streamlit`
- `pandas`
- `numpy`

## Ejecución

Para ejecutar la aplicación, abre una terminal en el directorio del proyecto y usa el siguiente comando:

```bash
pip install -r requirements.txt
streamlit run main.py
```

La simulación se abrirá automáticamente en tu navegador web predeterminado.

También este proyecto está preconfigurado para ejecutarse automáticamente en la nube. No es necesario instalar Python localmente ni ejecutar comandos manuales en la terminal para obtener los resultados.

## Pasos para Lanzar la Aplicación el la nube:
1.Crear el Entorno: Haz clic en el botón verde "<> Code" en la parte superior de este repositorio.

2.Iniciar Codespace: Selecciona la pestaña "Codespaces" y haz clic en "Create codespace on main".

3.Configuración Automática: Espera unos instantes. GitHub realizará lo siguiente de forma automática.

4.Ver la Aplicación: Aparecerá una notificación en la esquina inferior derecha indicando: "Your application running on port 8501 is available". Haz clic en el botón "Open in Browser" (Abrir en el navegador).
