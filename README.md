# Simulación de direccionamiento relativo

Simulación interactiva desarrollada en **Python mediante Google Colab**, que permite comprender cómo funciona el direccionamiento relativo y cómo se calcula una dirección de memoria utilizando una dirección base y un desplazamiento.

## 📌 ¿Qué es el direccionamiento relativo?

El direccionamiento relativo es una técnica utilizada en los sistemas computacionales para calcular una dirección de memoria tomando como referencia una dirección base y sumándole un desplazamiento (*offset*).

Esto permite acceder a diferentes posiciones de memoria sin necesidad de indicar directamente una dirección absoluta.

## 🎯 Objetivo de la simulación

Mostrar de manera práctica cómo se calcula una dirección efectiva mediante una dirección base y un desplazamiento.

La simulación permite modificar estos valores y observar cómo cambia el resultado.

## ⚙️ ¿Cómo funciona?

La simulación utiliza tres elementos principales:

- **Dirección base:** dirección que se toma como punto de referencia.
- **Desplazamiento (offset):** cantidad de posiciones que se suman a la dirección base.
- **Dirección efectiva:** dirección final obtenida después de realizar la suma.

### Fórmula

**Dirección efectiva = Dirección base + Desplazamiento**

### Ejemplo práctico

Supongamos que tenemos los siguientes valores:

| Elemento | Valor |
|---|---|
| Dirección base | 1000 |
| Desplazamiento | 256 |
| Dirección efectiva | 1256 |

**Cálculo:**

```text
Dirección base:       1000
Desplazamiento:      + 256
                     ------
Dirección efectiva:   1256
```

Esto significa que, tomando como referencia la dirección 1000 y avanzando 256 posiciones, se obtiene la dirección efectiva **1256**.

Si modificamos la dirección base o el desplazamiento, el resultado también cambiará.

## 🚀 Ejecutar la simulación

Puedes abrir la simulación directamente en Google Colab:

[![Abrir en Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AlejandraIbarraOrtiz/Simulacion-Direccionamiento-Relativo/blob/main/Simulaci%C3%B3n_Direccionamiento_Relativo.ipynb)

### Pasos para utilizarla

1. Haz clic en **Abrir en Google Colab**.
2. Espera a que cargue el cuaderno.
3. Ejecuta la celda de código utilizando el botón de reproducción.
4. Ingresa los valores de la dirección base y el desplazamiento.
5. Observa el resultado de la simulación.
6. Modifica los valores para comprobar cómo cambia la dirección efectiva.

## 🛠️ Herramientas utilizadas

- **Python:** lenguaje utilizado para desarrollar la simulación.
- **Google Colab:** entorno para ejecutar el código desde el navegador.
- **ipywidgets:** biblioteca utilizada para crear controles interactivos.
- **GitHub:** plataforma para almacenar y compartir el proyecto.

## 📝 Conclusión

Esta simulación permite comprender de manera sencilla cómo funciona el direccionamiento relativo, mostrando la relación entre la dirección base, el desplazamiento y la dirección efectiva.

Además, permite experimentar con diferentes valores para observar cómo se calcula una nueva dirección de memoria.
