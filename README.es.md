<p align="center">
  <img src="assets/icon.png" width="96" height="96" alt="Icono de MioType">
</p>

<h1 align="center">MioType</h1>

<p align="center">
  <b>Habla, no escribas.</b> Dictado por voz y traducción instantánea para Mac.<br>
  Pulsa <kbd>Fn</kbd>, habla, pulsa <kbd>Fn</kbd> otra vez y el texto aparece en tu cursor, en cualquier app.
</p>

<p align="center">
  <a href="https://miotype.com/download"><b>Descargar para macOS</b></a> ·
  <a href="https://miotype.com">Sitio web</a> ·
  <a href="https://miotype.com/pricing">Precios</a>
</p>

<p align="center"><sub><a href="README.md">English</a> · <a href="README.zh-CN.md">简体中文</a> · <a href="README.de.md">Deutsch</a> · <a href="README.es.md">Español</a> · <a href="README.fr.md">Français</a> · <a href="README.it.md">Italiano</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.pt.md">Português</a> · <a href="README.ru.md">Русский</a></sub></p>

---

Tu cursor puede estar en una terminal, en VS Code, en Cursor, en el prompt de Claude Code o Codex, en un hilo de Slack o en un mensaje de commit. A MioType le da igual: escribe donde esté el foco.

## Atajos

| Teclas | Qué hace |
|---|---|
| <kbd>Fn</kbd> | Pulsa para empezar a hablar y otra vez para escribirlo. <kbd>Esc</kbd> cancela |
| <kbd>Fn</kbd> + <kbd>Space</kbd> | Pregunta lo que quieras. Selecciona texto antes para preguntar sobre él, o di «hazlo más corto» para reescribirlo en su sitio |
| <kbd>Fn</kbd> + <kbd>Left Shift</kbd> | Habla en chino y obtén inglés, y al revés |
| <kbd>Fn</kbd> + <kbd>Control</kbd> | Traduce la selección. Una sola palabra en inglés abre una ficha de diccionario |
| <kbd>Fn</kbd> + <kbd>R</kbd> | Pule la selección en su sitio |
| <kbd>Fn</kbd> + <kbd>S</kbd> | Busca una palabra o expresión |

Todos los atajos se pueden cambiar en Configuración.

## Por qué gusta a los desarrolladores

- **Escribe donde está tu cursor.** Sin ventana aparte y sin copiar y pegar. Dicta un prompt largo para tu agente de código, la descripción de un PR o la respuesta a un issue justo donde va.
- **El chino mezclado con inglés se queda mezclado.** Si dices «把这个 function 改成 async», obtienes exactamente eso. Los términos en inglés no se traducen al chino.
- **Aprende tu vocabulario.** Corrige una palabra mal reconocida justo después de dictar (`kubectl`, `useEffect`, el nombre de un compañero) y MioType la añade a tu diccionario para acertar la próxima vez. También puedes importar un diccionario.
- **Sin conexión, con un solo interruptor.** Elige el modelo Whisper local en Configuración y tu voz nunca sale de tu Mac. Funciona sin red y sin cuenta.
- **Usa tu propia clave.** El reconocimiento y el pulido pueden ir a tu propio proveedor de API en lugar de MioType Cloud.

## Gratis y de pago

| | |
|---|---|
| **Local** | Gratis para siempre. Dictado sin conexión con Whisper, y traducción y pulido con tu propia clave de API. El historial, el diccionario y la configuración se quedan en tu Mac |
| **Nube gratuita** | Inicia sesión y obtén 3.000 palabras en la nube cada semana |
| **MioType Cloud** | 100.000 palabras en la nube al mes para reconocimiento en la nube, pulido y traducción con IA, sin clave de API propia. 9,99 US$/mes, 59,99 US$/año o 149 US$ en un solo pago |

Más detalles en la [página de precios](https://miotype.com/pricing). Cualquier compra se reembolsa en 14 días, sin preguntas.

## Privacidad

- Whisper local se ejecuta por completo en tu Mac.
- En modo nube, el audio o el texto de cada solicitud pasa por nuestro servidor hasta Alibaba Cloud Model Studio y el resultado vuelve directamente a ti. Nuestro servidor no guarda audio ni texto; solo registra el número de palabras, el tipo y la hora de la solicitud para calcular tu cuota.
- Con tu propia clave, las solicitudes van directamente desde tu Mac al proveedor que elegiste.
- No entrenamos modelos con tu contenido y no usamos anuncios ni rastreadores.
- Política completa (en inglés): [miotype.com/privacy](https://miotype.com/privacy)

## Requisitos

- Un Mac con Apple silicon (M1 o posterior)
- Permisos de micrófono y accesibilidad. MioType te los pide durante la configuración

## Comentarios

¿Encontraste un error o quieres una función? [Abre un issue](https://github.com/miotype/miotype/issues/new/choose). Para temas privados, escribe a [hi@miotype.com](mailto:hi@miotype.com).

Las notas de cada versión se publican en [Releases](https://github.com/miotype/miotype/releases). Pulsa **Watch → Custom → Releases** para recibir avisos.

---

MioType no es de código abierto. Este repositorio aloja el seguimiento público de issues y las notas de versión.
