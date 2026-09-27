# Documentos legales de Aire sin sustos

Política de privacidad de la aplicación **Aire sin sustos**, que avisa del
polen, la calima y la calidad del aire en España y el resto de Europa, para
Android.

Este repositorio existe solo para servir esos documentos por HTTPS con una URL
pública y estable, que es requisito de Google Play y del mensaje de
consentimiento de AdMob. **No contiene el código de la aplicación.**

| Documento | |
|---|---|
| Política de privacidad (español) | [privacidad-es.html](privacidad-es.html) |
| Privacy Policy (English) | [privacy-en.html](privacy-en.html) |

Se publica con GitHub Pages desde la rama `main`. El historial de commits sirve
además como registro de qué decía la política en cada momento, que en un
documento legal no es un detalle menor.

La URL base se pasa a la app al compilar, con
`--dart-define=PRIVACY_URL=https://demual.github.io/aire-sin-sustos-legal/`, y
la app elige el documento por idioma: `privacidad-es.html` en español y
`privacy-en.html` en cualquier otro.

---

Aire sin sustos · JR Soft, nombre comercial de Javier Román Sáez ·
`com.jrsoft.alergiasaire`

Los datos del polen, la calima y la calidad del aire contienen información
modificada del Servicio de Vigilancia Atmosférica de Copernicus, y la previsión
del tiempo es de MET Norway, ambas con licencia
[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Esta aplicación no
está afiliada a Copernicus, al ECMWF ni a MET Norway.
