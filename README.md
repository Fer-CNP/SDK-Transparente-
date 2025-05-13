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

1. Clona o descarga este repositorio.
2. Abre el archivo `sdk/index.html` directamente en tu navegador.

> No se requiere instalación ni servidor web. Todos los recursos están incluidos localmente.

## Pruebe su instalación

Para configurar sus propias credenciales de sandbox o producción, configure la siguiente información:
```
 <!-- Autenticación -->
    <script>
      const API_KEY = "Basic Y2EzYzY4Y2MtYmExNi00Y2JlLTkxMjYtMWNkOTVjZmU2Y2Y0OmY5ZjdjN2RlLTI5ODAtNDY2Ni05YjJlLTY5YzE2M2I0ZmNhZA==" //Aquí va tu API Key, no es necesario agregar nada más
      const token = "Basic Y2EzYzY4Y2MtYmExNi00Y2JlLTkxMjYtMWNkOTVjZmU2Y2Y0OmY5ZjdjN2RlLTI5ODAtNDY2Ni05YjJlLTY5YzE2M2I0ZmNhZA==";
```

## 🛠️ Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript (Vanilla)

## 🖼️ Capturas de pantalla (opcional)

_Agrega aquí capturas de la interfaz para mostrar el diseño._

## 📄 Licencia

Este proyecto se distribuye bajo la licencia MIT. Consulta el archivo `LICENSE` para más información.
