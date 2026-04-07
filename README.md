# Lojao-chines-catalogo
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lista de Preços Oficial - Loja o Chinês</title>
    <style>
        * { box-sizing: border-box; margin: 0; padding: 0; font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif; }
        body { background-color: #fafafa; padding-bottom: 100px; }

        /* Cabeçalho */
        header { background: #ffffff; padding: 15px; text-align: center; border-bottom: 1px solid #dbdbdb; position: sticky; top: 0; z-index: 1000; }
        .brand { font-size: 19px; font-weight: bold; color: #262626; text-transform: lowercase; }
        
        /* Banner de Frete Grátis */
        .frete-banner { background: #25d366; color: white; text-align: center; padding: 8px; font-size: 12px; font-weight: bold; text-transform: uppercase; }

        /* Título da Lista */
        .lista-header { padding: 20px 15px 10px 15px; background: white; border-bottom: 1px solid #eee; }
        .lista-header h1 { font-size: 14px; color: #8e8e8e; text-transform: uppercase; letter-spacing: 1px; }

        /* Container da Lista */
        .lista-container { background: white; padding: 0 15px; }

        /* Item da Lista */
        .lista-item { display: flex; justify-content: space-between; align-items: center; padding: 18px 0; border-bottom: 1px solid #f1f1f1; text-decoration: none; color: inherit; }
        .lista-item:active { background-color: #f9f9f9; }

        /* Detalhes do Produto */
        .prod-info { flex-grow: 1; padding-right: 10px; }
        .prod-nome { font-size: 15px; color: #262626; font-weight: 600; margin-bottom: 4px; }
        .prod-obs { font-size: 12px; color: #0095f6; font-weight: 500; }

        /* Preço */
        .prod-price-box { text-align: right; min-width: 90px; }
        .prod-price { font-size: 16px; font-weight: bold; color: #262626; }
        .p-unit { font-size: 10px; color: #8e8e8e; display: block; }

        /* Botão Flutuante Direct */
        .ig-float { position: fixed; bottom: 20px; right: 20px; background: linear-gradient(45deg, #f09433 0%,#e6683c 25%,#dc2743 50%,#cc2366 75%,#bc1888 100%); color: white; width: 60px; height: 60px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 28px; box-shadow: 0 4px 15px rgba(0,0,0,0.3); text-decoration: none; z-index: 2000; }
    </style>
</head>
<body>

    <header>
        <div class="brand">@lojaochines</div>
    </header>

    <div class="frete-banner">🚚 Frete Grátis para todo o Brasil</div>

    <div class="lista-header">
        <h1>📦 Ofertas do Dia</h1>
    </div>

    <div class="lista-container">

        <a href="https://ig.me/m/lojaochines" class="lista-item">
            <div class="prod-info">
                <div class="prod-nome">Copos Stitch</div>
                <div class="prod-obs">Cores variadas disponíveis</div>
            </div>
            <div class="prod-price-box">
                <div class="prod-price">Consulte</div>
            </div>
        </a>

        <a href="https://ig.me/m/lojaochines" class="lista-item">
            <div class="prod-info">
                <div class="prod-nome">Material Escolar (Canetas e +)</div>
                <div class="prod-obs">Variedade incrível</div>
            </div>
            <div class="prod-price-box">
                <span class="p-unit">A partir de</span>
                <div class="prod-price">R$ 2,99</div>
            </div>
        </a>

        <a href="https://ig.me/m/lojaochines" class="lista-item">
            <div class="prod-info">
                <div class="prod-nome">Kit de Maquiagem (30 Itens)</div>
                <div class="prod-obs">Qualquer kit da loja</div>
            </div>
            <div class="prod-price-box">
                <div class="prod-price">R$ 9,99</div>
            </div>
        </a>

        <a href="https://ig.me/m/lojaochines" class="lista-item">
            <div class="prod-info">
                <div class="prod-nome">Perfumes Variados</div>
                <div class="prod-obs">Fragrâncias exclusivas</div>
            </div>
            <div class="prod-price-box">
                <span class="p-unit">Máximo</span>
                <div class="prod-price">R$ 49,99</div>
            </div>
        </a>

        <a href="https://ig.me/m/lojaochines" class="lista-item">
            <div class="prod-info">
                <div class="prod-nome">Tablets (Cores Variadas)</div>
                <div class="prod-obs">Promoção p/ Atacado (5 unid.)</div>
            </div>
            <div class="prod-price-box">
                <div class="prod-price">R$ 19,99</div>
                <span class="p-unit">cada (Atacado)</span>
            </div>
        </a>

        <a href="https://ig.me/m/lojaochines" class="lista-item">
            <div class="prod-info">
                <div class="prod-nome">Tablet (Unidade)</div>
                <div class="prod-obs">Varejo</div>
            </div>
            <div class="prod-price-box">
                <div class="prod-price">R$ 29,99</div>
            </div>
        </a>

    </div>

    <a href="https://ig.me/m/lojaochines" class="ig-float" title="Chamar no Direct">📩</a>

    <p style="text-align: center; color: #8e8e8e; font-size: 11px; margin-top: 30px;">Toque no produto para pedir no Direct</p>

</body>
</html>
