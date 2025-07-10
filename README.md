<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Tu Página</title>
</head>
<body>

  <!-- Contenido de tu página aquí -->

  <!-- Chatbot WhatsApp Landbot -->
  <script>
    window.lbWhatsappWidgetSettings = {
      "avatar_url": "https://storage.googleapis.com/media.landbot.io/774092/web_widget/fda0ccf0-194f-4b2c-9767-aebec1097b01/avatar/avatar.jpg?1752104288765",
      "brand_name": "STRATECH Mesa de Servicio",
      "button_background_color": "#0f0c0c",
      "button_rounded_corners": "4",
      "button_text": "Envianos Un Mensaje!",
      "cta_text": "¡Iniciar Chat!",
      "input_color": "#0f0c0c",
      "welcome_text": "💬 ¡Hola, bienvenido/a a STRATECH! 🚀",
      "wa_phone": "5215651138365"
    };
  </script>
  <script src="https://static.landbot.io/livechat-widget/index.js" defer></script>

  <!-- Chatbot embebido Landbot (carga bajo interacción) -->
  <script>
    window.addEventListener('mouseover', initLandbot, { once: true });
    window.addEventListener('touchstart', initLandbot, { once: true });
    var myLandbot;
    function initLandbot() {
      if (!myLandbot) {
        var s = document.createElement('script');
        s.type = "module";
        s.async = true;
        s.addEventListener('load', function() {
          myLandbot = new Landbot.Livechat({
            configUrl: 'https://storage.googleapis.com/landbot.online/v3/H-3036895-6U7212WUR5KLBOBU/index.json',
          });
        });
        s.src = 'https://cdn.landbot.io/landbot-3/landbot-3.0.0.mjs';
        var x = document.getElementsByTagName('script')[0];
        x.parentNode.insertBefore(s, x);
      }
    }
  </script>

</body>
</html>
