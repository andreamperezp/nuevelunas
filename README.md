# Nueve Lunas

Acompañante digital de control prenatal para la madre gestante que no sabe por dónde empezar.

## Qué hace

- **Semana gestacional** a partir de la fecha de última regla (FUM) o la fecha probable de parto, con línea de tiempo por trimestre.
- **Calendario de controles** según la OMS (al menos 8 contactos) y aviso del próximo control.
- **Checklist de exámenes infaltables** por trimestre y posparto: para qué sirve cada uno, cómo prepararse, fecha y resultado.
- **Qué preguntar en cada consulta** según el trimestre, más preguntas propias, y un resumen copiable para llevar a la cita.
- **Señales de alarma** para consultar de inmediato, incluida la salud mental.

## Cómo usarla

Es una sola página sin dependencias de compilación: abre `index.html` en el navegador. Sin cuenta, los datos se guardan en el navegador (`localStorage`). Con "Mi cuenta" (enlace por correo) se guardan en Supabase, en la tabla `planes`, protegida con RLS para que cada usuaria solo vea su propio plan.

Para publicarla gratis: en GitHub, **Settings → Pages → Deploy from branch → main / root**.

## Fuentes

Recomendaciones de la OMS sobre atención prenatal (2016) y posnatal (2022), guías del ACOG y protocolos ministeriales de Latinoamérica.

> Nueve Lunas es una guía educativa y no reemplaza al equipo de salud. Los exámenes y las semanas exactas varían según el país y la historia de cada embarazo. Se recomienda revisión por un/a ginecoobstetra antes de su uso público.
