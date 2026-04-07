# Lojao-chines-catalogo
<!DOCTYPE html>
<html lang="pt-pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Catálogo Oficial - Loja o Chinês</title>
    <style>
        * { box-sizing: border-box; margin: 0; padding: 0; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; }
        body { background-color: #fafafa; padding-bottom: 80px; }

        /* Cabeçalho Estilo Instagram */
        header { background: #ffffff; padding: 15px; text-align: center; border-bottom: 1px solid #dbdbdb; position: sticky; top: 0; z-index: 1000; }
        .brand { font-size: 20px; font-weight: bold; color: #262626; text-transform: lowercase; }
        
        /* Barra de Busca */
        .search-container { padding: 10px 15px; }
        .search-bar { width: 100%; padding: 10px; border-radius: 8px; border: 1px solid #dbdbdb; background: #efefef; font-size: 14px; outline: none; text-align: center; }

        /* Categorias */
        .categories { display: flex; overflow-x: auto; padding: 10px 15px; gap: 8px; white-space: nowrap; scrollbar-width: none; }
        .cat-item { background: #fff; border: 1px solid #dbdbdb; padding: 6px 15px; border-radius: 15px; font-size: 12px; font-weight: 600; color: #262626; }
        .cat-item.active { background: #0095f6; color: white; border-color: #0095f6; }

        /* Grade de Produtos */
        .product-grid { display: grid; grid-template-columns: repeat(2, 1fr); gap: 10px; padding: 10px; }
        .product-card { background: white; border: 1px solid #dbdbdb; border-radius: 12px; overflow: hidden; display: flex; flex-direction: column; box-shadow: 0 2px 5px rgba(0,0,0,0.05); }
        .product-img { width: 100%; aspect-ratio: 1/1; object-fit: cover; }
        
        .product-info { padding: 12px; flex-grow: 1; display: flex; flex-direction: column; justify-content: space-between; }
        .p-title { font-size: 13px; color: #262626; line-height: 1.2; margin-bottom: 8px; height: 32px; overflow: hidden; display: -webkit-box; -webkit-line-clamp: 2; -webkit-box-orient: vertical; }
        .p-price { font-size: 17px; font-weight: bold; color: #262626; margin-bottom: 10px; }
        
        /* Botão Direct Instagram */
        .btn-buy { background: #0095f6; color: white; border: none; padding: 10px; border-radius: 6px; font-size: 12px; font-weight: bold; cursor: pointer; text-decoration: none; text-align: center; display: block; }
        .btn-buy:active { opacity: 0.7; transform: scale(0.98); }

        /* Botão Flutuante Direct Colorido */
        .ig-float { position: fixed; bottom: 20px; right: 20px; background: linear-gradient(45deg, #f09433 0%,#e6683c 25%,#dc2743 50%,#cc2366 75%,#bc1888 100%); color: white; width: 55px; height: 55px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 24px; box-shadow: 0 4px 15px rgba(0,0,0,0.4); text-decoration: none; z-index: 2000; }
    </style>
</head>
<body>

    <header>
        <div class="brand">@lojaochines</div>
    </header>

    <div class="search-container">
        <input type="text" class="search-bar" placeholder="O que procuras hoje?">
    </div>

    <div class="categories">
        <div class="cat-item active">🔥 Novidades</div>
        <div class="cat-item">🏠 Casa</div>
        <div class="cat-item">🎧 Eletrónicos</div>
        <div class="cat-item">✨ Ofertas</div>
    </div>

    <div class="product-grid">

        <div class="product-card">
            <img src="https://via.placeholder.com/300" class="product-img">
            <div class="product-info">
                <div class="p-title">Smartwatch D20 Bluetooth - Black Edition</div>
                <div class="p-price">R$ 27,90</div>
                <a href="https://ig.me/m/lojaochines" class="btn-buy">PEDIR NO DIRECT</a>
            </div>
        </div>

        <div class="product-card">
            <img src="https://via.placeholder.com/300" class="product-img">
            <div class="product-info">
                <div class="p-title">Fone i12 TWS Wireless Premium</div>
                <div class="p-price">R$ 19,90</div>
                <a href="https://ig.me/m/lojaochines" class="btn-buy">PEDIR NO DIRECT</a>
            </div>
        </div>

        </div>

    <a href="https://ig.me/m/lojaochines" class="ig-float" title="Falar no Direct">📩</a>

</body>
</html>
