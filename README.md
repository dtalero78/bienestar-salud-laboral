# Bienestar y Salud Laboral

Sitio web estático corporativo de **Bienestar y Salud Laboral (BSL)**.

- **Dominio:** [www.bienestarsaludlaboral.com](https://www.bienestarsaludlaboral.com)
- **Hosting:** GitHub Pages
- **Stack:** HTML, CSS y JS sin dependencias (single page)

## Estructura

- `index.html` — sitio completo (HTML + CSS + JS embebidos)
- `bsl-logo.png` — logo corporativo
- `CNAME` — dominio personalizado para GitHub Pages

## Servicios cubiertos en la página

1. Medicina ocupacional
2. Salud mental (psicología, psiquiatría y tamizaje psicológico)
3. Telemedicina particular
4. Plataformas y software médico (BRS, Consulta Bodytech, BSL Plataforma 2, RIPS Digital)

## Desarrollo local

Abre `index.html` directamente en el navegador, o sirve la carpeta:

```bash
python3 -m http.server 8080
```

## Deploy

Cualquier `push` a `main` despliega el sitio en GitHub Pages.
