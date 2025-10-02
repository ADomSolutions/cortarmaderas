# 🪚 Maderator 9000 — Optimizador de corte - DOMENICO ALEJANDRO

**Maderator 9000** es una aplicación web en HTML/JS que calcula la mejor forma de cortar una tabla de madera para **aprovechar al máximo el material**.  
Usa un algoritmo heurístico tipo *guillotine* para ubicar los pedazos y muestra el resultado en un **canvas interactivo**, con colores y métricas de aprovechamiento.

---

## 🚀 Características

- Entrada de **dimensiones de la tabla** (ancho, alto, grosor).  
- Carga de **pedazos con ancho, alto y cantidad**.  
- Opción de **rotar piezas 90°** automáticamente.  
- **Visualización en canvas** con colores únicos por pieza.  
- **Leyenda interactiva** y métricas de:
  - Aprovechamiento (%)
  - Desperdicio (%)
  - Cantidad de piezas ubicadas
- Exportación del plano a **PNG** listo para imprimir o enviar al taller.
- Modo **responsivo/compacto** para usar desde el celular.

---

## 🖥️ Demo rápida

1. Abrí `index.html` en tu navegador.
2. Configurá las medidas de la tabla.
3. Agregá pedazos (ejemplo: `40x20 cm`, cantidad 3).
4. Hacé click en **Calcular corte**.
5. El resultado aparece en el canvas con la disposición óptima y métricas.

---

## 📸 Capturas

<img width="1327" height="612" alt="image" src="https://github.com/user-attachments/assets/5a53f0fc-0c4c-4185-bc05-1fd956230db4" />


---

## ⚙️ Tecnologías usadas

- **HTML5** (estructura y formulario)
- **CSS3** (estilo moderno y responsivo)
- **JavaScript Vanilla** (algoritmo de corte + render en canvas)
- Algoritmo heurístico de tipo **guillotine packing**

---

## 📦 Instalación

No requiere instalación ni dependencias externas.

```bash
git clone https://github.com/turepo/maderator9000.git
cd maderator9000
# abrir index.html en tu navegador favorito

🤝 Contribuciones

¡Las PRs son bienvenidas!
Si encontrás un bug o querés sugerir una mejora, abrí un issue.

📜 Licencia

Este proyecto está bajo la licencia MIT.
Podés usarlo, modificarlo y adaptarlo libremente.

🪓 Grito de guerra!!!

“Maderator 9000: porque hasta la madera merece un plan maestro.”
