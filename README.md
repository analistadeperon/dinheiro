# dinheiro
<div id="app"></div>


    <body onload="mostrarResultado()">
        <main id="app" class="texto-centro">
            <header class="texto-principal">
                <h1>CONTROLE DE Dinheiro</h1>
            </header>
            <section id="dados" class="entrada-dados container">
                <p>Preencha os campos para adicionar ou remover um item! &#128230;</p>
                <input class="entradas" type="text" name="produto" id="produto" placeholder="Nome do Item" autocomplete="off"/></br>
                <input class="entradas" type="number" name="quantidade" id="quantidade" placeholder="Quantidade" autocomplete="off" input class="entradas"mode="numeric"/></br>
                <input class="entradas" type="number" name="preço" id="preço" placeholder="Preço R$" autocomplete="off" inputmode="numeric"/></br>
                <button class="botoes" name="adicionar" id="adicionar" onclick="verificar(), adicionar(), mostrarResultado()">ADICIONAR</button class="botoes">
                <button class="botoes" name="excluir" id="excluir" onclick="excluir(), mostrarResultado()">EXCLUIR</button>
            </section>
            <section id="estoque">
                <div id="comport-table">
                    <table class="saida-dados container" style="table-layout: fixed; width: 100%;">
                        <th>Saldo atual (SA)</th>
                        <th>Saldo diario (SD)</th>
                        <th>Saldo final (R$)</th>
                        <th>REMOVER</th>
                        <tbody id="resultados"></tbody>
                    </table>
                </div>
            </section>
        </main>
        <footer class="rodape texto-centro">
            COPYRIGHT &copy; 2021 | <a href="https://github.com/analistadeperon/" target="_blank">matheus</a>
        </footer>
        <script src="../src/main.js"></script>
    </body>
</html>
