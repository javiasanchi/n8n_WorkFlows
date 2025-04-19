# 🤖 Agente IA para Correo desde Telegram

Este workflow creado en n8n permite a un bot de Telegram recibir instrucciones de texto, generar un correo profesional con inteligencia artificial (GPT-4), consultar una hoja de contactos en Google Sheets y enviarlo automáticamente desde una cuenta de Gmail.

---

## 🧩 Componentes del flujo

- **Telegram Trigger** – Escucha los mensajes entrantes del usuario.
- **LangChain Agent + Memory** – Genera el contenido del correo con formato profesional.
- **Google Sheets Tool** – Extrae los contactos para encontrar destinatarios.
- **Gmail Tool** – Envía el correo al contacto seleccionado.
- **OpenAI GPT-4o mini** – Motor de IA para la generación del mensaje.

---

## ⚙️ Requisitos

1. Cuenta de Gmail con **API habilitada** y credenciales OAuth2 configuradas.
2. Hoja de cálculo en Google Sheets con lista de contactos (nombre, email).
3. Bot de Telegram activo con token de API configurado en n8n.
4. Clave API de OpenAI (GPT-4o).

---

## 🧪 Ejemplo de uso

Usuario envía desde Telegram:

```
envía un correo de agradecimiento a Laura por su ayuda en la sesión de fisioterapia
```

Y el agente responde automáticamente con:

```
Asunto: Agradecimiento por tu apoyo en la sesión

Cuerpo:
Hola Laura,  
Quiero expresarte mi sincero agradecimiento por tu valiosa colaboración en la sesión de fisioterapia. Tu apoyo ha sido fundamental para que todo saliera perfecto.  
Gracias nuevamente por tu compromiso.  
Saludos cordiales,
```

---

## 🗂 Archivo

`Basicos/Agente_Telegram.json`

---

## ✍️ Autor

Javi Sanchi – Automatizaciones con IA para emprendedores y pequeñas empresas.  
https://github.com/javiasanchi
