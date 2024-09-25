<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sklep z roślinami</title>
</head>
<body>
    <h1>Witamy w naszym sklepie z roślinami</h1>
    <p>Zapisz się na nasz newsletter, aby otrzymać najnowsze oferty!</p>
    
    <!-- Formularz -->
    <form id="newsletter-form">
        <label for="name">Imię:</label><br>
        <input type="text" id="name" name="name" required><br><br>
        <label for="email">E-mail:</label><br>
        <input type="email" id="email" name="email" required><br><br>
        <button type="submit">Wyślij</button>
    </form>

    <!-- Google Tag Manager (head) -->
    <script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start': 
    new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0], 
    j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src= 
    'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f); 
    })(window,document,'script','dataLayer','GTM-XXXXXXX');</script>
    <!-- Koniec kodu GTM -->

    <!-- Google Tag Manager (noscript) -->
    <noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-XXXXXXX"
    height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
    <!-- Koniec kodu GTM -->
</body>
</html>

