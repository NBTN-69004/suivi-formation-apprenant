<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Campus Digital</title>
    <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;700&family=Bebas+Neue&display=swap" rel="stylesheet">
    <style>
        :root { --bg: #1a1c24; --surface: #23272e; --accent: #5865F2; --text: #ffffff; }
        body { background: var(--bg); color: var(--text); font-family: 'DM Sans', sans-serif; margin: 0; padding: 20px; text-align: center; }
        .card { background: var(--surface); padding: 30px; border-radius: 20px; max-width: 500px; margin: auto; border: 1px solid #3f4455; box-shadow: 0 10px 30px rgba(0,0,0,0.5); }
        .logo { width: 120px; height: 120px; border-radius: 50%; border: 3px solid var(--accent); margin-bottom: 20px; }
        h1 { font-family: 'Bebas Neue', sans-serif; font-size: 32px; letter-spacing: 1px; margin: 10px 0; }
        p { color: #949ba4; font-size: 14px; }
        .btn { display: inline-block; background: var(--accent); color: white; padding: 12px 25px; border-radius: 30px; text-decoration: none; margin-top: 20px; font-weight: bold; }
    </style>
</head>
<body>
    <div class="card">
        <img src="https://i.postimg.cc/8PzL7GfL/image.png" class="logo" alt="Logo">
        <h1>CAMPUS DIGITAL</h1>
        <p>"L'échec est un diplôme"</p>
        <div style="border-top: 1px solid #3f4455; margin: 20px 0; padding-top: 20px;">
            <p>Plateforme en cours de déploiement...</p>
            <a href="#" class="btn" onclick="alert('Chargement du suivi...')">Accéder à mon suivi</a>
        </div>
    </div>
</body>
</html>
