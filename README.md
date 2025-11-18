<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Entrar no Grupo</title>
    <script>
        const linkAnuncio = "https://otieu.com/4/1020019";
        const linkDestino = "https://chat.whatsapp.com/LuRohRp3AUWIIbgDqc2KDu?mode=wwt";

        function entrar() {
            window.open(linkAnuncio, "_blank");
            setTimeout(() => {
                window.location.href = linkDestino;
            }, 2000);
        }
    </script>
</head>
<body style="font-family: Arial; background:#fafafa; text-align: center; padding-top: 100px;">
    <h2 style="color:#222;">Entrar no Grupo do WhatsApp</h2>
    <button onclick="entrar()" style="background:#25D366; padding:18px 35px; border:none; border-radius:10px; color:white; font-size:20px; cursor:pointer;">
      Entrar no Grupo
    </button>
    <p style="margin-top:20px; color:#666">
        Clique no botão para continuar.<br>
        O anúncio abre primeiro e depois o grupo do WhatsApp.
    </p>
</body>
</html>
