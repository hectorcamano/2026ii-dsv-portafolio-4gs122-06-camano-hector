# Práctica 2 — Maquetación de componentes de ConSentidos

**Sitio de la Clínica Veterinaria ConSentidos**
Desarrollo de Software V · Módulo III: Páginas web y CSS · Unidad 2
Prof. José Peralta B. · Universidad Tecnológica de Panamá, Centro Regional de Veraguas

---

## Qué contiene este paquete

| Archivo | Qué es |
| --- | --- |
| `assets/css/maquetacion.css` | Tu hoja de maquetación, con sus secciones comentadas. La completas tú. |
| `assets/img/servicios/consulta.jpg` | Foto horizontal (1200 × 700). |
| `assets/img/servicios/vacunacion.jpg` | Foto vertical (600 × 900). |
| `assets/img/servicios/desparasitacion.jpg` | Foto cuadrada (800 × 800). |
| `assets/img/servicios/cirugia.jpg` | Foto panorámica (1500 × 600). |
| `assets/img/servicios/jornada-rabia.jpg` | Foto vertical (720 × 960) para la figura flotante. |
| `README.md` | Este archivo. Sustituye al de la Práctica 1. |

Las fotos tienen **proporciones distintas a propósito**: la práctica consiste,
entre otras cosas, en que se vean uniformes sin deformarse.

## Qué vas a hacer

Vas a maquetar cuatro componentes del sitio con lo visto en la Unidad 2, sin
Flexbox ni Grid:

1. **Miniaturas** de los servicios con `float`, `clear`, `aspect-ratio` y
   `object-fit`.
2. Una **figura flotante** que el texto rodea, envuelta con `display: flow-root`.
3. Un **acceso de urgencias** siempre visible con `position: fixed`.
4. **Términos del glosario** que se quedan pegados con `position: sticky`.
5. Comprobar que **no hay desplazamiento horizontal a 360 px**.

## Dónde va

```
docs/modulos/m03-css/p02-maquetacion/
```

Cuando termines:

```
p02-maquetacion/
├── README.md              ← este archivo
├── index.html             ← enlace a maquetacion.css y acceso de urgencias
├── servicios.html         ← ídem + miniaturas, figura y glosario ampliado
├── componentes.html       ← enlace y acceso de urgencias
├── tarifas.html           ← ídem
├── cita.html              ← ídem
├── revision.html          ← ídem
├── paginas/
│   └── test.html          ← sin cambios
└── assets/
    ├── css/
    │   ├── consentidos.css   ← sin cambios
    │   ├── tema.css          ← el de tu Práctica 1, sin cambios
    │   └── maquetacion.css   ← nuevo, de este paquete
    └── img/
        └── servicios/        ← nuevo, de este paquete
```

## Cómo empezar

1. Copia **toda** la carpeta `docs/modulos/m03-css/p01-tema-visual/` y pégala
   como `docs/modulos/m03-css/p02-maquetacion/`.
2. Sustituye su `README.md` por el de este paquete y copia la carpeta
   `assets/` del paquete encima de la que ya tienes (solo añade archivos).
3. Abre con **Live Server** y sigue la guía.

## Antes de entregar

1. Revisa las seis páginas con cabecera publicadas, a 360 px y en escritorio,
   con la consola abierta (**F12** o **Ctrl+Shift+I**).
2. Registra la ficha de la práctica en `docs/modulos/index.html`.
3. Confirma y sube:

   ```bash
   git add docs/modulos/m03-css/p02-maquetacion docs/modulos/index.html
   git commit -m "M03 Práctica 2: maquetación de componentes"
   git push
   ```

4. Sube a Moodle el PDF de evidencia, con el nombre exacto
   `4GS121-NN_Apellido-Nombre_M03_Pra02.pdf`.

## Recuerda

- `consentidos.css` y `tema.css` no se modifican: todo tu trabajo va en
  `maquetacion.css`.
- Nada de `!important` ni de valores de `z-index` como `9999`.
- Tu identificación sigue **en la cabecera** de todas las páginas.
