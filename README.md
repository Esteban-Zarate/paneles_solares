# ☀️ EcoVolt Pro — Esteban Zarate

**Plataforma inteligente para energía solar fotovoltaica y sostenibilidad.**

## Identidad visual

EcoVolt Pro utiliza una jerarquía corporativa basada en una paleta estricta:

| Uso | Color | HEX |
|---|---|---|
| Fondo principal | Blanco / gris ultra claro | `#F8F9FA` |
| H1 / H2 | Azul Marino Oscuro | `#0B2545` |
| Subtítulos / conceptos ecológicos | Verde Energía | `#2E7D32` |
| CTA / acciones críticas | Amarillo Sol / Naranja Cálido | `#FF9F1C` |
| Superficies | Blanco puro | `#FFFFFF` |

Los botones CTA utilizan texto **Azul Marino Oscuro** sobre `#FF9F1C` para mantener un contraste fuerte y legible.

## Funciones

- Dimensionamiento de sistemas fotovoltaicos.
- Tabla y análisis de cargas.
- Sistemas OFF-GRID, ON-GRID e híbridos.
- Cálculos de paneles, baterías, inversores y cableado.
- Presupuestos, cotizaciones y mano de obra.
- Simulación y generación de reportes.
- Gestión de usuarios y permisos.
- Base de datos SQLite.

## Ejecución

```bash
pip install -r requirements.txt
streamlit run solar_app.py
```

## GitHub

```bash
git add .
git commit -m "Actualizar diseño corporativo EcoVolt Pro"
git push -u origin main
```

Repositorio: `Esteban-Zarate/paneles_solares`

## Autor

**Esteban Zarate**

> **EcoVolt Pro — Tecnología solar para un futuro sostenible.** ☀️🌱
## 🔐 Contraseñas y secretos

- Las contraseñas de las cuentas se almacenan en `solar_calc.db` únicamente como hash.
- La contraseña inicial del superadministrador se puede definir en `.streamlit/secrets.toml`.
- `.streamlit/secrets.toml`, `solar_calc.db` y los archivos de credenciales están excluidos de Git mediante `.gitignore`.
- Para producción, cambia las contraseñas de prueba desde **Seguridad → Gestión de usuarios → Reset contraseña**.

### Credenciales actuales de prueba
- `admin` → `EcoVolt#2026_Admin!`
- `prueba` → `EcoVolt#2026_Prueba!`
- `usuario1` → `EcoVolt#2026_Usuario1!`
- `usuario2` → `EcoVolt#2026_Usuario2!`

> Si por `secret.tool` te referías al sistema de secretos de Streamlit, el archivo correcto es `.streamlit/secrets.toml`.

