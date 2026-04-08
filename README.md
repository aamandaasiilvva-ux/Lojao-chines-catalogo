# Lojao-chines-catalogo

  <!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Catálogo Oficial - Loja o Chinês</title>
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
        .lista-item { display: flex; justify-content: space-between; align-items: center; padding: 18px 0; border-bottom: 1px solid #f1f1f1; text-decoration: none; color: inherit; transition: 0.2s; }
        .lista-item:active { background-color: #f9f9f9; }

        /* Detalhes do Produto */
        .prod-info { flex-grow: 1; padding-right: 10px; }
        .prod-nome { font-size: 15px; color: #262626; font-weight: 600; margin-bottom: 4px; }
        .prod-obs { font-size: 12px; color: #25d366; font-weight: 500; }

        /* Preço */
        .prod-price-box { text-align: right; min-width: 90px; }
        .prod-price { font-size: 16px; font-weight: bold; color: #262626; }
        .p-unit { font-size: 10px; color: #8e8e8e; display: block; }

        /* Botão Flutuante WhatsApp */
        .wa-float { position: fixed; bottom: 20px; right: 20px; background: #25d366; color: white; width: 60px; height: 60px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 30px; box-shadow: 0 4px 15px rgba(0,0,0,0.3); text-decoration: none; z-index: 2000; }
    </style>
</head>
<body>

    <header>
        <div class="brand">@lojaochines</div>
    </header>

    <div class="frete-banner">🚚 Frete Grátis para todo o Brasil</div>

    <div class="lista-header">
        <h1>📦 Catálogo de Ofertas</h1>
    </div>

    <div class="lista-container">

        <a href="https://wa.me/5563992112184?text=Olá! Vi no catálogo e tenho interesse nos Copos do Stitch." class="lista-item">
            <div class="prod-info">
                <div class="prod-nome">Copos Stitch</div>
                <div class="prod-obs">Cores variadas disponíveis</div>
            </div>
            <div class="prod-price-box">
                <div class="prod-price">Ver Catálogo</div>
            </div>
        </a>

        <a href="https://wa.me/5563992112184?text=Olá! Vi no catálogo e quero saber mais sobre o Material Escolar de R$ 2,99." class="lista-item">
            <div class="prod-info">
                <div class="prod-nome">Material Escolar (Canetas e +)</div>
                <div class="prod-obs">Variedade completa</div>
            </div>
            <div class="prod-price-box">
                <span class="p-unit">A partir de</span>
                <div class="prod-price">R$ 2,99</div>
            </div>
        </a>

        <a href="https://wa.me/5563992112184?text=Olá! Vi no catálogo e quero o Kit de Maquiagem com 30 itens por R$ 9,99." class="lista-item">
            <div class="prod-info">
                <div class="prod-nome">Kit de Maquiagem (30 Itens)</div>
                <div class="prod-obs">Qualquer kit selecionado</div>
            </div>
            <div class="prod-price-box">
                <div class="prod-price">R$ 9,99</div>
            </div>
        </a>

        <a href="https://wa.me/5563992112184?text=Olá! Vi no catálogo e quero ver as fragrâncias dos perfumes de R$ 49,99." class="lista-item">
            <div class="prod-info">
                <div class="prod-nome">Perfumes Variados</div>
                <div class="prod-obs">Fragrâncias Premium</div>
            </div>
            <div class="prod-price-box">
                <span class="p-unit">Até</span>
                <div class="prod-price">R$ 49,99</div>
            </div>
        </a>

        <a href="https://wa.me/5563992112184?text=Olá! Vi no catálogo e tenho interesse no Tablet no ATACADO (5 unidades)." class="lista-item">
            <div class="prod-info">
                <div class="prod-nome">Tablets (Atacado - 5 unid.)</div>
                <div class="prod-obs">Cores variadas</div>
            </div>
            <div class="prod-price-box">
                <div class="prod-price">R$ 19,99</div>
                <span class="p-unit">cada</span>
            </div>
        </a>

        <a href="https://wa.me/5563992112184?text=Olá! Vi no catálogo e tenho interesse no Tablet (Varejo)." class="lista-item">
            <div class="prod-info">
                <div class="prod-nome">Tablet (Unidade única)</div>
                <div class="prod-obs">Varejo</div>
            </div>
            <div class="prod-price-box">
                <div class="prod-price">R$ 29,99</div>
            </div>
        </a>

    </div>

    <a href="https://wa.me/5563992112184" class="wa-float" title="Chamar no WhatsApp">
        <svg style="width:32px;height:32px" viewBox="0 0 24 24">
            <path fill="currentColor" d="M12.04 2C6.58 2 2.13 6.45 2.13 11.91C2.13 13.66 2.59 15.36 3.45 16.86L2.05 22L7.3 20.62C8.75 21.41 10.38 21.83 12.04 21.83C17.5 21.83 21.95 17.38 21.95 11.92C21.95 9.27 20.92 6.78 19.05 4.91C17.18 3.03 14.69 2 12.04 2M12.05 3.67C14.25 3.67 16.31 4.53 17.87 6.09C19.42 7.65 20.28 9.72 20.28 11.92C20.28 16.46 16.58 20.15 12.04 20.15C10.66 20.15 9.3 19.81 8.1 19.14L7.78 18.97L4.62 19.81L5.46 16.71L5.28 16.42C4.54 15.23 4.15 13.86 4.15 11.91C4.15 7.37 7.84 3.67 12.05 3.67M8.53 7.33C8.37 7.33 8.1 7.39 7.87 7.64C7.65 7.89 7 8.5 7 9.71C7 10.93 7.89 12.1 8.02 12.26C8.14 12.44 9.76 14.94 12.25 16.03C12.84 16.28 13.3 16.42 13.66 16.53C14.25 16.72 14.79 16.69 15.23 16.63C15.72 16.55 16.72 16.02 16.92 15.44C17.13 14.87 17.13 14.38 17.07 14.28C17.01 14.18 16.85 14.12 16.6 14C16.36 13.88 15.14 13.28 14.92 13.2C14.7 13.12 14.54 13.08 14.38 13.33C14.21 13.58 13.75 14.12 13.61 14.28C13.47 14.44 13.33 14.46 13.08 14.33C12.84 14.21 12.06 13.95 11.13 13.13C10.41 12.48 9.92 11.68 9.78 11.44C9.64 11.19 9.77 11.06 9.89 10.94C10 10.83 10.12 10.67 10.25 10.5C10.37 10.33 10.41 10.21 10.5 10.04C10.58 9.88 10.54 9.74 10.48 9.61C10.42 9.47 9.92 8.25 9.71 7.75C9.51 7.25 9.3 7.31 9.15 7.31C9 7.31 8.82 7.33 8.53 7.33Z" />
        </svg>
    </a>

    <p style="text-align: center; color: #8e8e8e; font-size: 11px; margin-top: 30px; padding: 0 20px;">
        Toque no produto para consultar estoque e cores no WhatsApp.
    </p>

</body>
</html>
