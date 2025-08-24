# 🍳 Simulación de Cocina con Gemini 1.5 Pro

Este proyecto es una **demostración de cómo usar inteligencia artificial para planificar y ejecutar tareas paso a paso**.  
El escenario elegido es una **cocina virtual**, donde la IA (Gemini 1.5 Pro) decide qué hacer en cada ciclo hasta completar todo el proceso de preparar la comida, servirla y limpiar.

La IA toma decisiones en orden lógico, por ejemplo:
1. Reunir ingredientes  
2. Encender la estufa  
3. Cocinar la comida  
4. Servirla  
5. Limpiar  
6. Finalizar  

---

## 🚀 Instalación
```bash
pip install google-generativeai
```

## 🧑‍💻 Uso
Ejecuta el script principal para iniciar la simulación:
```bash
python main.py
```

## 📊 Ejemplo de Ejecución
```bash
➡️ Acción sugerida: get_ingredients
🧠 Razonamiento: Primero necesitamos reunir los ingredientes antes de cocinar.

➡️ Acción sugerida: turn_on_stove
🧠 Razonamiento: Encendemos la estufa para poder cocinar.

➡️ Acción sugerida: cook
🧠 Razonamiento: Con ingredientes listos y estufa encendida, podemos cocinar.
...
✅ El proceso de cocina ha finalizado.
```

## 🎯 ¿Para qué sirve este código?
- Ejemplo educativo de cómo integrar Gemini 1.5 Pro en un entorno controlado.
- Simulación paso a paso de toma de decisiones.
- Demostración práctica de cómo estructurar prompts y leer respuestas en formato JSON.
- Puede adaptarse a otros entornos (por ejemplo: logística, tareas de oficina, flujos de trabajo).
