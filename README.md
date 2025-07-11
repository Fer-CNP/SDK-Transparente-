# 💳 Demo SDK Checkout Transparente

Este proyecto es un ejemplo de integración visual de un **Checkout Transparente** utilizando un SDK web. La demo incluye estilos, componentes visuales y un flujo básico de navegación para simular la experiencia de pago en línea.

## 📁 Estructura del proyecto

```
sdk/
├── index.html                  # Página principal de la demo
├── style.css                   # Estilos globales
├── assets/                     # Recursos gráficos (íconos, imágenes)
│   ├── logo-clip.png
│   ├── credit_card.svg
│   └── ...
├── components/                 # Estilos de componentes del checkout
│   ├── order.css
│   ├── nav.css
│   ├── checkout-container.css
│   └── tab.css
└── js/
    └── tab.js                  # Lógica JS para navegación por pestañas
```

## 🚀 Cómo ejecutar la demo

1. Clona o descarga este repositorio, git clone https://github.com/COMPLEMENTAR LA URL
2. Abre el archivo `sdk/index.html` en un editor de texto y despúes puedes ejucutarlo directemente en tu navegador web

> No se requiere instalación ni servidor web. Todos los recursos están incluidos localmente.

## Pruebe su instalación

Para configurar sus propias credenciales de sandbox o producción, configure la siguiente información en la línea 168 y 169 (consumir la Apis Keys de Producción o Pruebas):


```ruby
 <!-- Autenticación -->
    <script>
      const API_KEY = "tu-Basic ejemplo YWJhNWJkNjQtOTYwOC00N2E4LWIwMzUtNWU2NDkzOTBjZTViOmY2NmI0MzVkLTFmYTEtNDk5NC0wMmI2LTBiYTYzMmJhMThiZA== " //Aquí va tu API Key, no es necesario agregar nada más
      const token = "tu-Basic ejemplo Basic YWJhNWJkNjQtOTYwOC00N2E4LWIwMzUtNWU2NDkzOTBjZTViOmY2NmI0MzVkLTFmYTEtNDk5NC0wMmI2LTBiYTYzMmJhMThiZA==";
...

```

y la línea 423 (consumir solo la Apis Keys de Producción):

```ruby

 async function checkout(token) {
        const options = {
          method: 'POST',
          headers: {
            'Authorization': 'tu-Basic ejemplo Basic YWJhNWJkNjQtOTYwOC00N2E4LWIwMzUtNWU2NDkzOTBjZTViOmY2NmI0MzVkLTFmYTEtNDk5NC0wMmI2LTBiYTYzMmJhMThiZA==',
            'accept': 'application/json', 
            'content-type': 'application/json'
          },
...

```

## 🛠️ Tecnologías utilizadas 

- HTML5
- CSS3
- JavaScript (Vanilla)

## 🖼️ Capturas de pantalla (opcional)

<img width="1370" alt="Captura de pantalla 2025-05-13 a la(s) 3 54 57 p m" src="https://github.com/user-attachments/assets/4018095c-8381-4b51-a376-2b014988ce16" />



## 📄 Licencia

Este proyecto se distribuye bajo la licencia MIT. Consulta el archivo `LICENSE` para más información.
