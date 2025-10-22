Integrantes: Mateus Cavalheiro, Brian Fachini e Vinicius Goedert - MA 77

Descrição: IA's Conta é um software de gestão financeira pessoal que utiliza inteligência artificial para organizar, analisar e sugerir estratégias de economia com base nas informações fornecidas pelo usuário. O sistema permite:
Cadastrar receitas e despesas manualmente 
Criar e acompanhar metas financeiras 
Receber recomendações inteligentes de economia 
Simular diferentes cenários financeiros 
____________________________________________________________________
Requisitos Funcionais (RF)
RF1 - Gestão de Dados Financeiros:
O sistema deve permitir o gerenciamento dos dados financeiros do usuário (fontes de receita e despesas).
RF2 - Análise e Organização Financeira:
O sistema deve organizar as finanças do usuário e sugerir uma divisão percentual do dinheiro com base nas preferências do usuário.
RF3 - Recomendação de Estratégias de Economia:
O sistema deve gerar sugestões de estratégias para o usuário economizar dinheiro.
RF4 - Exportação de planilhas:
O sistema deve fornecer uma planilha excel com todas as informações cadastradas quando solicitado.
RF5 - Monitoramento de Desempenho Financeiro:
O sistema deve permitir o acompanhamento financeiro com base nas informações recebidas pelo usuário. 
RF6 - Autenticação:                                                                                                                                  O sistema deve permitir a autenticação de usuários.
RF7 - Personalização de metas:
O sistema deve permitir que o usuário defina metas financeiras personalizadas (como poupar para uma viagem, quitar dívidas ou investir) e acompanhar o progresso em relação a essas metas.
RF8 - Histórico financeiro:
O sistema deve manter um histórico dos planejamentos financeiros realizados, permitindo ao usuário visualizar versões anteriores e comparar a evolução das estratégias.
RF9 - Simulação de cenários:
O sistema deve permitir que o usuário simule diferentes cenários financeiros (como aumento de receita ou corte de despesas) e visualizar os impactos dessas mudanças na organização do dinheiro.
RF10 - Classificação Inteligente de despesas:
O sistema deve utilizar a rede neural para classificar automaticamente as despesas informadas pelo usuário em categorias (como essenciais, supérfluas, recorrentes), facilitando a análise e o planejamento.
________________________________________________________________________
Requisitos Não Funcionais (RNF)
RNF1 - Usabilidade:
 A interface do usuário deve ser intuitiva e fácil de usar.
RNF2 - Performance:
 O sistema deve processar e analisar dados financeiros de forma eficiente, com mínima latência.
RNF3 - Escalabilidade:
 O sistema deve ser escalável, permitindo adicionar novas funcionalidades sem impacto significativo.
RNF4 - Segurança:
 O sistema deve garantir a segurança dos dados financeiros dos usuários (por meio de criptografia e autenticação robusta).
RNF5 - Confiabilidade:
 O sistema deve ser confiável, com baixo índice de falhas, especialmente nas funções críticas.
RNF6 - Privacidade:
 O sistema deve aderir às leis de proteção de dados e garantir controle do usuário sobre seus dados.
RNF7 - Compatibilidade:
 O sistema deve ser compatível com diferentes navegadores.
RNF8 - Manutenibilidade:
 O código do sistema deve ser bem estruturado, modular e documentado.
_________________________________________________________________________
Regras de Negócio (RN)
RN1 - Cada usuário pode realizar, no máximo, 20 operações financeiras (cadastro, alteração ou exclusão de receitas, despesas e metas) em um intervalo de 12 horas, conforme política de estabilidade e uso responsável da plataforma.
RN2 - As recomendações de estratégias de economia só podem ser geradas quando o usuário possuir, no mínimo, 5 despesas e 2 receitas cadastradas, garantindo a confiabilidade das análises.
RN3 - O sistema deve se certificar que toda meta deve conter um valor alvo e um prazo definido.
RN4 - Cada usuário poderá realizar apenas uma exportação de relatório financeiro por dia, contendo informações de data, categoria, valor e tipo de transação (receita ou despesa), em conformidade com as políticas de uso da plataforma.
RN5 - Simulações de cenários financeiros não podem ser convertidas em metas sem confirmação explícita do usuário.
