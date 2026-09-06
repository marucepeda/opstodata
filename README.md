# opstodata

Landing page de **opstodata** — consultoría de datos y automatización con IA para negocios operativos (e-commerce, logística, soporte).

🔗 [opstodata.com](https://opstodata.com)

## Estructura

```
├── index.html      # Landing page principal
├── 404.html        # Página de error personalizada
├── CNAME           # Dominio personalizado para GitHub Pages
└── robots.txt      # Indicaciones para buscadores
```

## Desarrollo local

Es un sitio estático, sin dependencias ni build. Para verlo localmente:

```bash
python3 -m http.server 8080
```

Y abrir `http://localhost:8080` en el navegador.

## Deploy

El sitio se publica automáticamente vía **GitHub Pages** desde la branch `main`, carpeta raíz. Cualquier cambio pusheado a `main` se refleja en producción en un par de minutos.

Configuración de DNS (Spaceship): 4 registros A apuntando a las IPs de GitHub Pages, más el archivo `CNAME` en el repo con `opstodata.com`.

## Licencia

Todos los derechos reservados © 2026 opstodata.
