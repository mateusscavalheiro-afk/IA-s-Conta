<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IA's Conta</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: #f5f5f5;
            color: #333;
            padding: 20px;
        }
        h1 {
            color: #2c3e50;
        }
        .section {
            background: #fff;
            border-radius: 8px;
            padding: 15px 20px;
            margin-bottom: 15px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        button {
            background: #3498db;
            color: white;
            border: none;
            padding: 10px 15px;
            border-radius: 5px;
            cursor: pointer;
            margin-bottom: 10px;
        }
        button:hover {
            background: #2980b9;
        }
        .content {
            display: none;
            margin-top: 10px;
        }
        ul {
            margin: 0;
            padding-left: 20px;
        }
    </style>
</head>
<body>

    <h1>IA's Conta</h1>

    <div class="section">
        <h2>Descrição</h2>
        <p><strong>IA's Conta</strong> é um software de gestão financeira pessoal que utiliza inteligência artificial para organizar, analisar e sugerir estratégias de economia com base nas informações fornecidas pelo usuário. O sistema permite cadastrar receitas, despesas e metas financeiras manualmente, receber recomendações inteligentes e acompanhar o progresso financeiro ao longo do tempo.</p>
        <p>O projeto não integra dados bancários reais, garantindo que todas as informações sejam simuladas e seguras.</p>
    </div>

    <div class="section">
        <h2>Objetivos</h2>
        <button onclick="toggleContent('objetivos')">Mostrar/Esconder Objetivos</button>
        <div class="content" id="objetivos">
            <ul>
                <li>Organizar as finanças pessoais de forma prática e eficiente.</li>
                <li>Classificar automaticamente despesas em categorias (essenciais, supérfluas, recorrentes) usando rede neural.</li>
                <li>Fornecer recomendações personalizadas de economia e planejamento financeiro.</li>
                <li>Simular diferentes cenários financeiros e analisar impactos de mudanças nas finanças.</li>
                <li>Exportar relatórios e histórico financeiro em planilhas Excel.</li>
                <li>Garantir segurança, privacidade e controle total do usuário sobre seus dados.</li>
            </ul>
        </div>
    </div>

    <div class="section">
        <h2>Envolvidos</h2>
        <button onclick="toggleContent('envolvidos')">Mostrar/Esconder Equipe</button>
        <div class="content" id="envolvidos">
            <ul>
                <li><strong>Mateus</strong> – Desenvolvimento e integração backend/IA</li>
                <li><strong>Brian</strong> – Frontend e dashboards Streamlit</li>
                <li><strong>Vinicius</strong> – Planejamento, organização do projeto e testes</li>
            </ul>
        </div>
    </div>

    <script>
        function toggleContent(id) {
            const elem = document.getElementById(id);
            if (elem.style.display === 'none' || elem.style.display === '') {
                elem.style.display = 'block';
            } else {
                elem.style.display = 'none';
            }
        }
    </script>

</body>
</html>
