Free-Mots - Sitio estático (imágenes fijas)
============================================
Este paquete NO tiene controles de subida. Las imágenes se toman de /assets.

Archivos clave en raíz:
- index.html
- vercel.json
- carpeta /assets con:
  - logo.svg
  - heno1.svg, heno2.svg, heno3.svg, heno4.svg
  - serv1.svg, serv2.svg

Cómo reemplazar por tus imágenes reales:
1) Cambia los archivos de /assets manteniendo los mismos nombres.
   - Ej.: reemplaza assets/logo.svg por assets/logo.png (puedes usar .png/.jpg).
2) Si cambias de .svg a .png, actualiza la extensión también en index.html.
   - Busca: assets/logo.svg → cámbialo por assets/logo.png
3) Sube todo al repositorio en la RAÍZ (index.html + vercel.json + carpeta assets).
4) Vercel desplegará automáticamente.

DNS (GoDaddy → Vercel):
- A @ → 76.76.21.21
- CNAME www → cname.vercel-dns.com.
