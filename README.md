# 🌳 Sistemas de Lindenmayer  

Este repositorio contiene el desarrollo del **Parcial II** de la asignatura *Vida Artificial*, que explora los **Sistemas de Lindenmayer** para la generación procedimental de bosques con perspectiva y puntos de fuga.  

## 📚 Descripción del proyecto  

El objetivo principal es simular un bosque natural utilizando principios de **Sistemas-L** y técnicas de perspectiva visual para representar profundidad. Esto incluye:  
- Diversidad de formas en las plantas generadas.  
- Perspectiva mediante puntos de fuga para mayor realismo.  
- Aleatoriedad en las plantas para evitar uniformidad.  
- Grupos de especies con características comunes, como color y forma.  

El bosque se genera dinámicamente, ofreciendo una nueva versión en cada ejecución del código, manteniendo coherencia visual y estructural.  

---

## ✨ Características principales  

1. **Sistemas-L**:  
   - Uso de al menos cinco tipos de reglas de producción diferentes.  
   - Incorporación de reglas aleatorias para variaciones individuales.  

2. **Puntos de fuga**:  
   - Uso de dos puntos de fuga para simular profundidad y perspectiva.  
   - Árboles en el fondo más pequeños para reforzar el efecto visual.  

3. **Agrupación de especies**:  
   - Plantas de la misma especie visualizadas con colores uniformes.  
   - Generación simultánea de todas las plantas para un efecto estético cohesivo.  

4. **Dinamismo**:  
   - Cada ejecución del código genera un bosque único.  
   - Conservación de patrones representativos con pequeñas variaciones aleatorias.  

5. **Versiones del bosque**:  
   - Al menos tres versiones diferentes del bosque se generan con el mismo código.  

---

## 🛠 Tecnologías utilizadas  

- **Python**: Para implementar los sistemas de Lindenmayer y la visualización.  
- **Bibliotecas sugeridas**:  
  - `matplotlib` o `turtle` para la representación gráfica.  
  - `random` para la inclusión de aleatoriedad.  

---

## 🚀 Instrucciones de uso  

1. Clona el repositorio:  
   ```bash
   git clone https://github.com/IsabellaArdila/SistemasLindenmayer.git
   cd SistemasLindenmayer
   ```  

2. Instala las dependencias necesarias (si aplica).  

3. Ejecuta el archivo principal:  
   ```bash
   python src/main.py
   ```  

4. Visualiza el bosque generado automáticamente.  
