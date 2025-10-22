Free-Mots - Sitio estático listo para Vercel
=================================================
Contenido:
- index.html  (incluye Tailwind por CDN y JS para cargar imágenes/local)
- assets/     (carpeta por si quieres poner imágenes fijas después)
- vercel.json (configuración básica para static)

Cómo desplegar en Vercel (drag & drop):
1) Ve a https://vercel.com → New Project → Deploy manually
2) Arrastra la carpeta completa 'freemots_static_site_full' o el ZIP
3) Cuando termine, agrega tu dominio en Settings → Domains
4) En GoDaddy, crea/ajusta los DNS:
   - A @ → 76.76.21.21
   - CNAME www → cname.vercel-dns.com.
5) Verifica el dominio en Vercel y espera la propagación (minutos).

Cambios rápidos:
- Edita el número de WhatsApp en el input (visible en la página) o directamente en index.html (valor por defecto: 525572217853).
- El correo predeterminado es ventasfreemots@gmail.com (puedes cambiarlo en index.html).

Notas:
- La carga de imágenes es local (no se suben a servidor). Ideal para vista previa y demostración.
- Para imágenes permanentes, colócalas en /assets y enlázalas en el HTML.
