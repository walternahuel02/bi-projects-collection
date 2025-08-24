# 🏦 Monitoreo Financiero : Pagos, Impuestos y Bancos.

Este proyecto presenta un **dashboard interactivo** con la información de una empresa que gestiona cobros y pagos con distintos clientes a través de diferentes bancos y formas de pago.
El objetivo es analizar transacciones y métodos de pago por banco.

## 📊 Vista del Dashboard

![Dashboard Ventas Tech](https://raw.github.com/walternahuel02/bi-projects-collection/main/Monitoreo-Financiero:-Pagos-Impuestos-y-Bancos/assets/visual1.jpg)

## 🗂️ Estructura de los datos

El dataset contiene información de ventas con las siguientes columnas:

- **Número de movimiento** → Identificación única
- **Nombre** → Cliente con el que interactúa.
- **Ciudad** → Ubicación
- **Fecha de movimiento** 
- **Valor de movimiento** 
- **Tipo** → Dirección del flujo monetario (pagado, recibido).
- **Banco**   
- **Imagen** → Recurso visual del banco. 
- **Forma de pago** → Plataforma de pago.

## 📈 Principales insights del dashboard

- Pagos recibidos y realizados: Visualización del flujo total de ingresos y egresos.
- Impuestos y utilidad: Cálculo de la carga tributaria y del beneficio neto.
- Evolución mensual de la utilidad: Gráfico de cascada que refleja incrementos y disminuciones mes a mes.
- Participación por banco: Análisis comparativo de pagos recibidos por cada institución bancaria.
- Métodos de pago: Segmentación de transacciones con tarjeta frente a otros medios, destacando su representatividad en el total.
- Márgenes operativos: Indicador de rentabilidad expresado en porcentaje.

###### nota: para el cálculo de impuestos se usó el valor del 5% por movimiento.

-----------------------------------------------------------
## 📊 Informe de Conclusiones 

### 🔹 Comparación entre bancos  
- **ICBC** recibe un volumen de pagos **mayor al de Santander (casi el doble)**.  
- Sin embargo, el **margen de utilidad de ICBC es menor al 12%**, lo que indica baja rentabilidad respecto al total procesado.  
- En contraste, **Santander**, con un volumen menor, alcanza un **margen del 88%**, siendo el más rentable entre todos los bancos analizados.  

---

### 🔹 Banco Nación como punto de equilibrio  
- **Banco Nación** se posiciona como el banco con mejor **balance entre volumen de pagos y rentabilidad**.  
- Reporta una utilidad neta de **$15 millones de pesos**, convirtiéndose en el socio financiero más estable en términos de resultados.  

---

### 🔹 Uso de tarjetas  
- El **promedio general de transacciones con tarjeta es del 31%**.  
- **Citigroup y BBVA** superan este promedio, lo que evidencia una mayor adopción de medios electrónicos de pago en estas instituciones.  

---

### 🔹 Resultados mensuales por banco  
- En el mes de **abril**, tanto **ICBC, BBVA y Banco Nación** reportaron **saldos deudores**.  
- En cambio, **Santander y Citigroup** lograron mantener **saldos acreedores de manera constante en todos los meses del período analizado**.  

---

### 📌 Conclusión general  
- **ICBC** → Líder en volumen, pero con bajo margen de utilidad.  
- **Santander** → Menor volumen, pero con la **mayor rentabilidad (88%)**.  
- **Banco Nación** → Mejor equilibrio entre ingresos y utilidad.  

## ⚙️ Tecnologías utilizadas

- Excel / Power BI (visualización de datos)  
- Dataset en formato CSV/Excel  
- GitHub para versionado y publicación  

---

✨ Proyecto creado con fines de análisis de datos y visualización.  
