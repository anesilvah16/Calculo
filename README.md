## IMPORTANTE ##
    Você tem todo o direito de usar esse material 
    para seu próprio aprendizado. Professores também 
    podem ter acesso a todo o conteúdo e usá-los com 
    seus alunos. Porém todos os que usarem esse 
    material - seja para qual for a finalidade - deverão 
    manter a referência ao material original, disponível 
    em https://github.com/gustavoguanabara/javascript. Este 
    material não poderá ser utilizado em nenhuma hipótese 
    para ser replicada - integral ou parcialmente - 
    por autores/editoras/instituições para criar livros 
    ou apostilas, com finalidades de obter ganho financeiro 
    com ele.
-->

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interação JS</title>
    <style>
        body { font: 12pt Arial; }
        button { font-size: 12pt; padding: 30px; }
    </style>
</head>
<body><h1>Interagindo com um botão</h1>
    <button onclick="clicou()">Clica em mim!</button>
    <script>
        function clicou() {
            window.alert('Você clicou no botão!')
        }
    </script>
</body>
</html>
