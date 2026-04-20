# MAXIFER - Panel de Control

Suite de herramientas administrativas internas para MAXIFER.

## Estructura

```
/
├── index.html          ← Hub principal (panel)
├── costos/
│   └── index.html      ← Módulo Costos y Fábricas
├── pedidos/
│   └── index.html      ← Módulo Pedidos a Fábrica
└── gastos/             ← (próximamente)
    └── index.html
```

## Deploy en GitHub Pages

1. Subir todos los archivos al repo manteniendo la estructura
2. En Settings → Pages, activar "Deploy from a branch" con branch `main` y folder `/ (root)`
3. Acceder desde `https://<usuario>.github.io/<repo>/`

## Configuración

Al abrir el panel por primera vez, pide los links de Google Drive de cada archivo Excel. Los links se guardan en `localStorage` del navegador.

## Módulos

- **Costos y Fábricas**: lee `01_COMPRAS - COSTOS - FABRICAS.xlsm`
- **Pedidos a Fábrica**: lee `03_Pedidos_Fabricas.xlsm`
- **Gastos**: pendiente
