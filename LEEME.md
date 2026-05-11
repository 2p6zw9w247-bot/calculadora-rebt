# Calculadora de Caída de Tensión — REBT ITC-BT-19

Aplicación web progresiva (PWA) para el cálculo de caída de tensión en instalaciones
eléctricas de baja tensión según la normativa española vigente (REBT).

## Cómo instalar (sin necesidad de tiendas de apps)

### Windows (Chrome / Edge)
1. Abre el archivo `index.html` en Chrome o Edge
   → O súbelo a un servidor web y accede desde la URL
2. En la barra de direcciones aparecerá un icono de instalación (➕ o pantalla con flecha)
3. Haz clic en "Instalar" → la app aparecerá en el escritorio y el menú inicio

### Android (Chrome)
1. Abre Chrome y navega hasta la URL donde hayas alojado el archivo
2. Aparecerá un banner "Añadir a pantalla de inicio" o "Instalar app"
3. Confirma → la app aparece como cualquier aplicación nativa

### iPhone / iPad (Safari)
1. Abre Safari y navega a la URL
2. Toca el botón Compartir (cuadrado con flecha hacia arriba)
3. Selecciona "Añadir a pantalla de inicio"
4. Confirma el nombre y toca "Añadir"

## Uso sin servidor (abrir directamente el archivo)

Para Windows: puedes abrir `index.html` directamente con doble clic.
La calculadora funciona, pero sin offline ni instalación como app.
Para offline completo e instalación, necesitas alojarlo en un servidor HTTPS.

## Opciones gratuitas para alojar la app (offline + instalable)

- **GitHub Pages**: sube los archivos a un repositorio GitHub → activa Pages → URL gratuita HTTPS
- **Netlify Drop**: arrastra la carpeta a netlify.com/drop → URL instantánea HTTPS
- **Vercel**: conecta el repositorio → despliegue automático

## Normativa aplicada

- REBT RD 842/2002 con modificaciones vigentes
- ITC-BT-19: Instalaciones interiores — límites de CDT
- RD 1955/2000: Tensiones normalizadas (230V/400V)
- UNE 20460: Conductividades de referencia (Cu=56, Al=35 m/Ω·mm²)
