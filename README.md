<!DOCTYPE html>
<html lang="bg">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NOA bar&brunch | Пловдив</title>
    <style>
        :root {
            --gold: #c5a059;
            --dark: #1a1a1a;
            --light: #f4f4f4;
        }
        body { font-family: 'Segoe UI', sans-serif; margin: 0; background: var(--light); color: var(--dark); line-height: 1.6; }
        
        /* Header */
        header { background: var(--dark); color: white; padding: 60px 20px; text-align: center; }
        header h1 { margin: 0; font-size: 3rem; letter-spacing: 4px; color: var(--gold); }
        header p { font-style: italic; opacity: 0.8; }

        /* Menu Section */
        .container { max-width: 900px; margin: auto; padding: 20px; }
        .menu-category { margin-top: 40px; border-bottom: 2px solid var(--gold); padding-bottom: 10px; }
        .menu-item { display: flex; justify-content: space-between; margin: 15px 0; align-items: baseline; }
        .menu-item h3 { margin: 0; font-size: 1.1rem; }
        .price { font-weight: bold; color: var(--gold); min-width: 80px; text-align: right; }
        .description { font-size: 0.9rem; color: #666; display: block; max-width: 80%; }

        /* CTA Button */
        .btn-call { display: block; width: fit-content; margin: 40px auto; background: var(--gold); color: white; 
                    padding: 15px 30px; text-decoration: none; border-radius: 5px; font-weight: bold; }

        /* Footer */
        footer { background: var(--dark); color: white; text-align: center; padding: 40px; margin-top: 50px; }
    </style>
</head>
<body>

<header>
    <h1>NOA</h1>
    <p>bar & brunch | Пловдив, ул. Септември</p>
</header>

<div class="container">
    <h2 class="menu-category">Основни ястия</h2>
    
    <div class="menu-item">
        <div>
            <h3>Кралски Котлет Томахоук</h3>
            <span class="description">С намачкани пресни картофи с масло и балкански билки - 450г</span>
        </div>
        <span class="price">15,33 €</span>
    </div>

    <div class="menu-item">
        <div>
            <h3>Сьомга Рустик</h3>
            <span class="description">Сочно филе от сьомга с черен ориз, пюре от грах и сос холандес - 350г</span>
        </div>
        <span class="price">18,40 €</span>
    </div>

    <h2 class="menu-category">Десерти</h2>
    
    <div class="menu-item">
        <div>
            <h3>Сан Себастиян</h3>
            <span class="description">Печен чийзкейк по оригинална рецепта - 200г</span>
        </div>
        <span class="price">7,97 €</span>
    </div>

    <div class="menu-item">
        <div>
            <h3>Кето Пистачио</h3>
            <span class="description">Блат с бадемово брашно, шоколадов ганаж без захар и 100% паста Пистачио</span>
        </div>
        <span class="price">9,19 €</span>
    </div>

    <a href="tel:0895707707" class="btn-call">ЗАПАЗИ МАСА: 089 570 7707</a>
</div>

<footer>
    <p>Работно време: Всеки ден до 00:00 ч.</p>
    <p>📍 Пловдив, ул. Септември (Район Западен)</p>
</footer>

</body>
</html>
