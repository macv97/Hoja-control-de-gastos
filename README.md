# 📊 Control de Gastos Personal & Planificador Financiero Inteligente

Bienvenido al sistema avanzado de **Control de Gastos Personal y Planificador Financiero**. Este ecosistema de hojas de cálculo ha sido diseñado bajo estándares profesionales de análisis financiero y banca privada para proporcionarte una visibilidad absoluta sobre tu salud económica, optimizar tu tasa de ahorro y proyectar tu patrimonio a largo plazo de forma dinámica y visualmente premium.

El sistema está optimizado para su uso en **Excel** o **Google Sheets**, siendo ideal para subirse a **Google Drive** y gestionarse cómodamente a diario desde cualquier dispositivo.

---

## 🚀 Funcionalidades Clave

### 1. 🎛️ Cuadro de Mando Interactivo (Dashboard Único)
La pieza central de tu análisis financiero. A través de un diseño limpio con estética corporativa premium, te ofrece:
*   **Selector de Año Dinámico (Celda C3):** Cambia el año de visualización (2026-2030) con un solo clic y observa cómo todo el cuadro de mando se recalcula instantáneamente mediante fórmulas inteligentes basadas en `INDIRECT`.
*   **Tarjetas de KPIs Automatizadas:**
    *   **Ingresos Acumulados:** Suma total de entradas del año seleccionado.
    *   **Gastos Acumulados:** Suma total de salidas del año seleccionado.
    *   **Ahorro Neto Acumulado:** Balance neto anual destacado visualmente (verde para positivo, rojo para negativo).
    *   **Tasa de Ahorro Promedio:** El indicador clave de eficiencia financiera (Ahorro Neto / Ingresos).
*   **Visualización Científica de Tendencias:**
    *   📊 **Evolución de Ingresos y Gastos:** Gráfico de columnas que compara tus flujos de caja mes a mes.
    *   📈 **Tendencia de la Tasa de Ahorro:** Línea suavizada de última generación que se autoajusta dinámicamente a los valores del año en curso. Los meses futuros sin transacciones se omiten de la gráfica (gracias a fórmulas que propagan valores vacíos `""` en lugar de ceros artificiales), evitando líneas planas que distorsionen la escala.
    *   🍕 **Distribución del Gasto por Categoría:** Gráfico circular interactivo que desglosa porcentualmente en qué se destina tu capital.

### 2. 📅 Hojas de Registro de Transacciones Anuales (`Gastos e Ingresos 2026-2030`)
Diseñadas para minimizar el error humano y acelerar la entrada de datos:
*   **Selector de Fecha Ergonómico:** Celda de fecha configurada con validación nativa. Al hacer doble clic en Google Sheets o Excel, se despliega un **calendario visual interactivo** para que nunca más tengas que escribir fechas a mano.
*   **Categorización Estricta:** Desplegables inteligentes alimentados por una hoja central de categorías para asegurar la consistencia del análisis.
*   **Detección Visual de Transacciones:** Columna de "Tipo" (Ingreso/Gasto) que se auto-estila dinámicamente:
    *   🟩 **Ingreso:** Resaltado en verde pastel con tipografía verde oscura.
    *   🟥 **Gasto:** Resaltado en rojo pastel con tipografía roja oscura.
*   **Diseño Antifatiga:** Alternancia sutil de filas (cebras) y anchos de columna optimizados para una lectura cómoda.

### 3. 📊 Matriz de Resumen Mensual Inteligente
Una hoja por cada año que consolida de forma transparente la información diaria de transacciones:
*   **Fórmulas Matriciales no Invasivas:** Utiliza combinaciones robustas de `SUMIFS`, `COUNTIFS` y `DATE` para extraer y consolidar importes sin necesidad de columnas auxiliares en el registro de gastos.
*   **Cero Datos Fantasma:** Los meses que aún no han transcurrido no muestran molestos ceros (`0.00 €` o `0.0%`), manteniéndose limpios para no ensuciar tus análisis intermedios ni tus gráficos.
*   **Resaltado Inteligente:** El ahorro neto mensual y anual cuenta con formato condicional semafórico para alertar sobre periodos de desahorro.

### 4. 🎯 Planificación de Objetivos & Simulador Financiero a 25 Años
Una potente herramienta de proyección patrimonial y coste de oportunidad:
*   **Simulación Dinámica de Ingresos y Gastos:** Introduce tus ingresos mensuales y tus gastos ordinarios estimados para calcular instantáneamente tu capacidad de ahorro base.
*   **Simulador de Compras Importantes (Coche, Hipoteca, etc.):** Evalúa el impacto de adquirir un compromiso financiero a largo plazo (por ejemplo, una cuota de hipoteca o coche de 500 €/mes) y descubre el coste real de esa decisión.
*   **El Poder del Interés Compuesto:** Compara tu ahorro simple a **6 meses, 1 año, 3, 5, 10 y 25 años** frente a su equivalente invertido a una tasa de rendimiento anual configurable (por ejemplo, 4% anual).
*   **Cálculo de Impacto Neto (Coste de Oportunidad):** Te muestra con precisión quirúrgica cuántos miles de euros de diferencia real existen a largo plazo si decides realizar ese gasto adicional en lugar de mantener tu ritmo de inversión ordinario.

---

## 🛠️ Instrucciones de Puesta en Marcha

Para comenzar a utilizar tu control de gastos personal de forma diaria o compartirlo con tus allegados:

1.  **Sube tu archivo a Google Drive:**
    *   Sube el archivo `Control_Gastos_Completo.xlsx` (para uso personal con tus datos históricos de 2026) o `Control_Gastos_Plantilla.xlsx` (plantilla totalmente limpia) a tu cuenta de Google Drive.
    *   Haz clic derecho sobre el archivo en Drive y selecciona **Abrir con > Hojas de cálculo de Google**.
    *   Guárdalo como formato nativo de Google Sheets si deseas activar la máxima fluidez del calendario visual y los gráficos interactivos en la nube.
2.  **Configura tu Hoja de Categorías:**
    *   Accede a la pestaña `Categorías`.
    *   Si lo deseas, personaliza los nombres de las categorías de gasto y su tipo. Todo el sistema se adaptará automáticamente a tu nueva lista.
3.  **Registra tus primeros movimientos:**
    *   Ve a la pestaña del año actual (ej. `Gastos e Ingresos 2026`).
    *   Haz doble clic sobre la columna de fecha para seleccionar el día en el calendario, introduce una descripción, selecciona la categoría y el tipo desde los desplegables, y escribe el importe.
4.  **Consulta tu evolución:**
    *   Vuelve al `Cuadro de Mando` para deleitarte con tus gráficos y métricas consolidadas en tiempo real.

---

## 📂 Contenido del Repositorio

*   `Control_Gastos_Plantilla.xlsx`: La plantilla oficial en blanco y libre de transacciones de ejemplo, 100% limpia y lista para ser compartida o iniciada desde cero por cualquier usuario.
*   `README.md`: Este manual de uso detallado con la arquitectura financiera del documento.

---

*Desarrollado con rigor analítico por un equipo de analistas financieros y de software. Lleva tu gestión financiera personal al siguiente nivel.* 📈
