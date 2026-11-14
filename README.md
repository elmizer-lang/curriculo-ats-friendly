# Curriculo-ats-friendly
Otimizador de currículos para sistemas ATS baseado em IA e Vibe Coding

# Problema
Muitos profissionais não conseguem acessar às vagas desejadas e nem sempre é a falta de conhecimento ou experiência adquirida. Senão que você pode ficar de fora pelo filtro ATS que faz com que o seu curriculo nem sequer fosse considerado antes de chegar a um analista humano que possa validar ele. Assim, você fica no caminho, confuso porque a oportunidade parecia perfeita para você e casava muito bem com seu perfil e a sua experiência.

# Solução
Um aplicativo simples que ajude às pessoas a encontrar a vaga ideal, e também ofereça sugestões e dicas para adequar o perfil à vaga desejada. A ideia é analisar a sinergia entre o currículo e a vaga, e ajudar a conectar adequar melhor os currículos em relação à vaga desejada. Além disso, formatar o currículo para passar o filtro ATS e assim ter mais oportunidades de ser aceito.

# Prompt usado no Lovable
Quero criar uma aplicação web que compara um currículo com uma vaga e devolve uma versão ATS friendly desse currículo. ATS é o Application Tracking System, o sistema que ranqueia candidatos antes de qualquer pessoa do RH ler alguma coisa. Siga a base do meu PRD (product requirements document) adjunto.

PRD - Career Match ATS
Visão Geral
O Career Match ATS é uma aplicação web desenvolvida para ajudar profissionais a aumentar suas chances de aprovação em processos seletivos modernos.

A plataforma compara um currículo com uma descrição de vaga, identifica o nível de aderência entre ambos e gera uma versão ATS Friendly do currículo, sem inventar experiências, certificações ou competências inexistentes.

O objetivo do MVP é validar se usuários encontram valor em receber feedback imediato sobre a compatibilidade entre seu currículo e uma vaga específica e obter sugestões práticas para aumentar suas chances de avançar para as próximas etapas de recrutamento.

Problema
Milhares de profissionais deixam de participar de processos seletivos não por falta de qualificação, mas porque seus currículos não conseguem passar pelos filtros automatizados utilizados pelas empresas.

Os ATS (Applicant Tracking Systems) analisam palavras-chave, competências, experiências e organização das informações antes mesmo que um recrutador visualize o currículo.

Isso gera frustração para candidatos que possuem experiência compatível com a vaga, mas não conseguem comunicar essa compatibilidade adequadamente para os sistemas de triagem.

Objetivo do Produto
Permitir que qualquer profissional:

Compare seu currículo com uma vaga.
Entenda seu nível de aderência.
Identifique lacunas de palavras-chave.
Receba recomendações de melhoria.
Gere uma versão ATS Friendly do currículo.
Visualize um ATS Readiness Score.
Exporte o currículo otimizado em formato DOCX.
Aumente suas chances de passar pelos filtros automatizados.
Público-Alvo
Primário
Profissionais em busca de recolocação.
Secundário
Recém-formados.
Profissionais em transição de carreira.
Pessoas que desejam crescimento profissional.
Profissionais buscando vagas internacionais.
Freelancers migrando para posições corporativas.
Proposta de Valor
"Descubra o quão compatível você é com uma vaga e transforme seu currículo em uma versão otimizada para ATS em poucos minutos."

Escopo do MVP
O MVP deve ser extremamente simples e focado na validação da proposta de valor.

Entrada
Usuário fornece:

Descrição da Vaga
Campo de texto para colar o conteúdo completo da vaga.

Currículo
Campo de texto para colar o currículo completo.

Fluxo Principal
Etapa 1 - Inserção dos Dados
Usuário:

Cola a descrição da vaga.
Cola o currículo.
Clica em "Analisar Compatibilidade".
Etapa 2 - Análise Inteligente
A IA executa:

Extração de Informações
Identifica:

Hard Skills
Soft Skills
Ferramentas
Tecnologias
Certificações
Idiomas
Comparação
Calcula:

Competências encontradas
Competências parcialmente encontradas
Competências ausentes
Compatibilidade
Produz:

Match Score
Explicação do Score
Insights
Recomendações
Etapa 3 - Resultado
Match Score
Exemplo:

83%

Faixas:

0% a 40% → Baixa aderência
41% a 70% → Média aderência
71% a 100% → Alta aderência
Palavras-Chave Encontradas
Exemplo:

SQL
Power BI
Scrum
Gestão de Projetos
Palavras-Chave Ausentes
Exemplo:

Azure
Tableau
Lean
Observação:

Exibir apenas palavras-chave presentes na vaga e ausentes no currículo.

Nunca assumir que o usuário possua determinada competência.

Insights
Exemplo:

"Seu currículo apresenta forte aderência em gestão de projetos e análise de dados. A vaga destaca Azure e Tableau como competências relevantes que não foram identificadas no currículo enviado."

Recomendações
Exemplos:

Destacar competências técnicas logo no resumo profissional.
Reorganizar a seção de experiência para evidenciar resultados.
Utilizar terminologia semelhante à da vaga apenas quando verdadeira.
Alerta Ético
Sempre exibir:

"O sistema nunca inventa experiências, certificações ou competências. Todas as recomendações são feitas exclusivamente a partir das informações fornecidas pelo usuário."

Etapa 4 - Currículo ATS Friendly
A IA gera uma nova versão otimizada do currículo.

Estrutura sugerida:

Resumo Profissional
Competências Técnicas
Experiência Profissional
Formação Acadêmica
Certificações
Idiomas
Objetivos:

Melhor organização
Melhor legibilidade
Melhor indexação ATS
Maior aproveitamento das palavras-chave existentes
Clareza profissional
Sem inventar qualquer informação.

ATS Readiness Score
Além do Match Score com a vaga, a aplicação exibe um indicador de qualidade ATS do currículo.

Exemplo:

ATS Readiness Score: 89/100

Critérios:

Estrutura
Organização
Clareza
Uso de palavras-chave
Legibilidade para ATS
Funcionalidades do MVP
F1 - Comparador Currículo x Vaga
Entradas:

Currículo
Descrição da vaga
Saídas:

Score
Análise
Recomendações
F2 - Detector de Palavras-Chave
Exibir:

Palavras encontradas
Palavras ausentes
F3 - Gerador ATS Friendly
Gerar currículo otimizado.

F4 - ATS Readiness Score
Gerar nota de qualidade ATS.

F5 - Exportação DOCX
Gerar arquivo DOCX contendo:

Currículo ATS Friendly
Estrutura formatada
Pronto para candidatura
Telas
Tela 1 - Landing Page
Hero
Título:

Descubra se o seu currículo está preparado para passar pelo ATS.

Subtítulo:

Compare seu currículo com uma vaga, encontre oportunidades de melhoria e gere uma versão otimizada em poucos minutos.

CTA Principal:

Analisar Currículo

Como Funciona
Passo 1

Cole a vaga.

Passo 2

Cole seu currículo.

Passo 3

Receba análise e versão ATS Friendly.

Benefícios
Mais clareza sobre aderência às vagas.
Melhor aproveitamento das palavras-chave.
Currículo otimizado para ATS.
Recomendações educativas.
Tela 2 - Comparação
Layout em duas colunas.

Coluna Esquerda
Descrição da vaga.

Coluna Direita
Currículo.

Botão principal:

Analisar Compatibilidade

Tela 3 - Resultado
Card Match Score
Percentual de aderência.

Card ATS Score
Pontuação ATS.

Card Palavras Encontradas
Lista de competências identificadas.

Card Palavras Ausentes
Lista de competências não identificadas.

Card Insights
Resumo explicativo.

Card Recomendações
Melhorias práticas.

Card Currículo ATS Friendly
Área editável contendo o currículo gerado.

Botões:

Copiar Currículo
Exportar DOCX
Nova Análise
Design System
Base
Utilizar exclusivamente:

shadcn/ui

Componentes:

Card
Button
Badge
Progress
Tabs
Alert
Input
Textarea
Dialog
Tooltip
Skeleton
Separator
Estilo Visual
Visual moderno e confiável.

Referências:

Stripe
Linear
Notion
Vercel
Características:

Design clean
Espaçamentos amplos
Bordas suaves
Tipografia legível
Pouco ruído visual
Mobile First
Paleta de Cores
Primária
Sage Green

#A8C3A0
Secundária
Soft Blue

#B8D8F8
Destaque
Lavender

#D6C2F0
Sucesso
#B7E4C7
Aviso
#FFE5B4
Erro
#FFCAD4
Fundo
#FAFAF8
Texto Principal
#2D3748
Texto Secundário
#718096
Regras de UX
Não exigir login.
Não exigir cadastro.
Fluxo em uma única jornada.
Mobile First.
Linguagem acessível.
Explicar claramente o score.
Nunca prometer contratação.
Nunca inventar experiências.
Priorizar clareza e velocidade.
Critérios de Sucesso
O usuário deve:

Entender o Match Score.
Entender o ATS Score.
Compreender os gaps encontrados.
Considerar úteis as recomendações.
Conseguir exportar o currículo.
Utilizar novamente a ferramenta.
Prompt da IA
Ao receber um currículo e uma descrição de vaga:

Extrair competências técnicas e comportamentais.
Comparar currículo e vaga.
Identificar competências encontradas.
Identificar competências ausentes.
Calcular um Match Score de 0 a 100.
Gerar ATS Readiness Score.
Explicar os motivos da pontuação.
Gerar recomendações práticas.
Reescrever o currículo para formato ATS Friendly.
Nunca inventar experiências ou certificações.
Priorizar apenas informações comprovadas no currículo.
Utilizar linguagem profissional e objetiva.
Diretriz para o Lovable
Construir uma aplicação web moderna em React utilizando shadcn/ui e Tailwind.

O MVP deve conter apenas três telas:

Landing Page
Tela de Análise
Tela de Resultado
O produto deve focar em validar rapidamente a proposta de valor de um analisador ATS, evitando funcionalidades avançadas como:

Login
Cadastro
Banco de currículos
Histórico
Matching automático de vagas
Integrações externas
Dashboard administrativo
Toda a experiência deve girar em torno de um único fluxo:

Colar Vaga → Colar Currículo → Analisar → Ver Match Score → Ver ATS Score → Ver Recomendações → Gerar ATS Friendly → Exportar DOCX

# Como funciona o app
O app é simples e procura analisar currículos de maneira rápida e em poucos clics. Na primeira tela tem um botão CTA para ir a tela de análise. Já na segunda tela é possível colar a vaga de preferência (por exemplo, do linkedIn), e colar o currículo em formato texto (futuramente será possível subir ele em formato PDF para que a conversão a texto seja automática). Com o segundo clic já vamos à terceira tela, a tela dos resultados.

Na tela do resultados podemos ver a adequação do perfil à vaga em percentagem. E também a adequação do CV ao sistema ATS. É possível identificar fortalezas e debilidades através das palavras-chave encontradas e as faltantes. É possível também ver quais são as hard skills e soft kills pedidas pela vaga que aparecem no currículo, com selector de categoria.

Além disso, o sistema entrega uma serie de insight e dicas para melhorar o currículo em relação à vaga. E finalmente tem a opção de exportar o arquivo em formato Docx, e até pode ser editado antes de exportar ele. Algumas funcionalidades como exportar em PDF e adicionar palavras chave faltantes ficaram de fora do MVP.

# Ajustes após a primeira geração
Eu quis fazer uma versão simples do aplicativo web, que execute somente o analise do currículo. Pelo que vi no exemplo da aula, dá para adicionar seções de acompanhamento nas vagas em que o usuário se candidatou. Mas também essas melhoras precisam de criação de usuário e login, coisa que eu decidi manter simples para testar o MVP, e também para consumir menos créditos do Lovable, considerando que estou criando três aplicativos ao mesmo tempo para finalizar o curso da Dio. Então, com o intuito de fazer o MVP para testar deixei essa funcionalidade de fora, mesmo assim, acho que a minha proposta pode dispensar disso.

O que eu faria seria melhorar o apartado visual, trabalhar o logotipo, talvez trabalhar com fotografia na landing page. Também gostaria de poder adicionar o curriculo em formato PDF e que a IA transforme ele em texto. Além disso, gostaria que ao gerar o curriculo ATS friendly tenha opção de adicionar automáticamente as palavras chave faltante (ou que usuário possa escolher quais palavras ou conhecimentos que faltam no CV mas ele tem, quer adicionar). 

Por falta de créditos, no consegui atualizar nesse ponto. Também gostaria exportar ele em formato PDF. Essas seriam as duas alterações que eu faria.

# Link da app web:
https://careermatchats.lovable.app/

Tela 1: Home
<img width="1515" height="843" alt="image" src="https://github.com/user-attachments/assets/ddc5f2d0-2389-45f2-b231-e763e7e11db8" />

Tela 2: Analisar Currículo
<img width="1320" height="845" alt="image" src="https://github.com/user-attachments/assets/821cf859-3583-4499-be4b-a69150364c63" />

Tela 3: Resultados
<img width="1330" height="827" alt="image" src="https://github.com/user-attachments/assets/1a086cbd-bf8b-43fd-83d2-58f76f0482b2" />

Tela 3: Palavras-chave encontradas e faltantes
<img width="1292" height="691" alt="image" src="https://github.com/user-attachments/assets/591d5f7f-6bcb-43c9-8f4f-c56e44816648" />

Tela 3: Habilidades da vaga por categoria
<img width="1301" height="816" alt="image" src="https://github.com/user-attachments/assets/e355dc92-a4c9-4fc6-9166-ceaca06a3982" />

Tela 3: Insights
<img width="1297" height="811" alt="image" src="https://github.com/user-attachments/assets/5ba8de6f-f110-4ad4-bd2f-d67d3645f083" />

Tela 3: Editar e exportar o currículo ATS Friendly em formato Docx
<img width="1350" height="843" alt="image" src="https://github.com/user-attachments/assets/de3eecaa-104c-4a1d-ad8e-562614629011" />




