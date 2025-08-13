# Introdução

Texto descritivo com a visão geral do projeto abordado. Inclui o contexto, o problema, os objetivos, a justificativa e o público-alvo do projeto.

## Problema
Em um cenário de crescente preocupação com o planejamento financeiro, muitas famílias e indivíduos estabelecem orçamentos rigorosos para suas despesas mensais, sendo as compras de supermercado um dos gastos mais significativos e variáveis. O problema central que observamos é a dificuldade e a ineficiência no controle de gastos em tempo real durante a realização de uma compra de grande volume. Frequentemente, consumidores com um orçamento pré-definido recorrem a métodos manuais, como o uso de papel, caneta e calculadora, ou mesmo o aplicativo de calculadora do celular, para somar o valor dos produtos à medida que os colocam no carrinho.

Este processo manual é suscetível a erros de cálculo, pode ser lento, e desvia a atenção do consumidor, tornando a experiência de compra mais estressante e menos eficiente. O ato de manusear uma lista de papel, uma caneta e um carrinho de compras em um ambiente movimentado como um supermercado ou "atacarejo" é inerentemente pouco prático. A consequência direta deste problema é o risco constante de ultrapassar o orçamento planejado, resultando em surpresas desagradáveis no caixa e potenciais desajustes no planejamento financeiro do mês.

## Objetivos

**Objetivo Geral:**

Desenvolver uma aplicação móvel para a plataforma Android que solucione a dificuldade de controle de gastos em tempo real durante compras de supermercado, servindo como uma ferramenta de auxílio para o cumprimento de um orçamento pré-definido.

**Objetivos Específicos:**

- Projetar uma interface de usuário (UI) intuitiva e de alta usabilidade, focada em minimizar o tempo de interação e a distração do usuário no ambiente dinâmico do supermercado.

- Implementar um sistema de cálculo em tempo real que permita ao usuário adicionar, editar e remover itens de forma ágil, garantindo a precisão e a atualização instantânea do valor total da compra.

- Estruturar uma base de dados local no dispositivo para permitir a criação e o salvamento de múltiplas listas de compras, oferecendo ao usuário a capacidade de se planejar antecipadamente.

## Justificativa

A motivação para o desenvolvimento deste projeto nasce de uma necessidade prática e amplamente reconhecida. Em uma era digital onde aplicativos otimizam inúmeras tarefas do dia a dia, desde transporte até serviços bancários, o controle de compras no supermercado permanece, para muitos, um processo analógico e ineficiente. A escolha deste tema se justifica pela oportunidade de aplicar conhecimentos em desenvolvimento móvel para criar uma solução de impacto direto na vida dos usuários, promovendo uma melhor gestão financeira e reduzindo o estresse associado às compras.

A escolha de focar na usabilidade (primeiro objetivo específico) é crucial, pois o sucesso da aplicação depende de sua capacidade de ser mais conveniente do que o método manual que visa substituir. Uma interface complexa ou lenta anularia o propósito da ferramenta. A ênfase na precisão e agilidade do sistema de cálculo (segundo objetivo específico) é a espinha dorsal do projeto; a confiança do usuário na aplicação depende inteiramente da exatidão dos valores apresentados. A digitalização desse processo não apenas previne erros matemáticos, mas também libera o usuário para focar no que realmente importa: a escolha dos melhores produtos pelo melhor preço, dentro de suas possibilidades financeiras.

## Público-Alvo

A aplicação destina-se a pessoas e famílias das classes C, D e E, para quem o controle rigoroso do orçamento de supermercado é uma necessidade crítica para a estabilidade financeira mensal. Este público depende de um planejamento minucioso para garantir que a renda, muitas vezes limitada e variável, seja suficiente para cobrir todas as despesas essenciais.

O perfil dos nossos usuários inclui chefes de família (homens e mulheres) que sustentam seus lares com rendas próximas a um ou dois salários mínimos, trabalhadores informais, diaristas, e jovens adultos em início de carreira com remuneração baixa. Essas pessoas realizam suas compras majoritariamente em "atacarejos" e supermercados populares, buscando ativamente por promoções e priorizando itens da cesta básica. A relação com a tecnologia é pragmática. A grande maioria possui um smartphone com sistema Android, frequentemente um modelo de entrada ou mais antigo, com capacidade de armazenamento e processamento limitadas. O acesso à internet móvel costuma ser por meio de planos pré-pagos, com pacotes de dados limitados, o que torna essencial que a aplicação seja leve, rápida e, crucialmente, funcione perfeitamente de forma offline durante o uso na loja. O conhecimento prévio se concentra em aplicativos de alta popularidade, como WhatsApp, Facebook e aplicativos de banco digital, portanto, a interface do nosso projeto precisa ser extremamente intuitiva, com ícones claros e uma jornada de uso que não exija aprendizado complexo. Para este público, o aplicativo não é um luxo, mas uma ferramenta de empoderamento e segurança financeira.

**Personas**
Para humanizar e detalhar este público, criamos duas novas personas:

**Persona 1:** Sônia, a Chefe de Família
Idade: 45 anos
Ocupação: Diarista (trabalha em 3 casas diferentes)
Família: Mãe solo, 2 filhos (10 e 15 anos)
Perfil Tecnológico: Possui um smartphone Android básico que ganhou de presente há 2 anos. Usa principalmente para WhatsApp e para ver vídeos no YouTube. Tem um plano de dados pré-pago que recarrega quando pode.
**Objetivos:**
Fazer a "compra grande" do mês com os R$ 650,00 que conseguiu juntar, sem deixar faltar o básico para os filhos.
Evitar a vergonha de ter que deixar produtos no caixa por não ter dinheiro suficiente.
Tentar economizar qualquer trocado para uma emergência ou para a conta de luz.
**Frustrações:**
"A cabeça fica a mil na hora da compra. É muita conta, muito preço pra lembrar. Sempre acho que esqueci de somar alguma coisa."
"O medo de passar do valor é constante. Já tive que escolher entre levar a mistura ou o material de limpeza."
"Meu celular é lento, não posso instalar muito aplicativo. E a internet no mercado quase nunca funciona."

**Persona 2:** Fábio, o Jovem Trabalhador
Idade: 19 anos
Ocupação: Repositor em um supermercado (primeiro emprego)
Família: Mora com a mãe e dois irmãos mais novos. Ajuda nas despesas de casa.
Perfil Tecnológico: Gosta de tecnologia e entende bem de celular, mas tem um modelo de entrada por limitações financeiras. Sabe identificar um aplicativo bom e funcional.
**Objetivos:**
Fazer a compra da quinzena com a parte do salário que separou (R$ 400,00), para mostrar à mãe que é responsável.
Fazer o dinheiro render ao máximo, comparando marcas e aproveitando as promoções que ele mesmo ajuda a etiquetar no trabalho.
Não precisar pedir dinheiro emprestado ou usar o limite do cartão da mãe.
**Frustrações:**
"Eu tento usar a calculadora, mas ficar trocando de tela toda hora me atrapalha e demora."
"Às vezes vejo uma promoção boa, mas fico na dúvida se posso pegar porque não sei quanto já deu o total no carrinho."
"Queria uma forma fácil de ver quanto eu tô gastando só com besteira e quanto é com comida de verdade."

<table>
  <thead>
    <tr>
      <th>Stakeholder</th>
      <th>Categoria</th>
      <th>Interesse no Projeto</th>
      <th>Influência no Projeto</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Usuários Finais</strong> (Ex: Sônia e Fábio)</td>
      <td>Externo</td>
      <td><strong>Necessidade crítica</strong> de uma ferramenta para controle financeiro; app funcional offline, leve e preciso.</td>
      <td>Alta (o sucesso do projeto depende 100% de atender às suas necessidades essenciais).</td>
    </tr>
    <tr>
      <td><strong>Equipe de Desenvolvimento</strong> (Nós)</td>
      <td>Interno</td>
      <td>Concluir o projeto com sucesso, aplicar conhecimentos, obter aprovação.</td>
      <td>Alta (responsáveis por todas as decisões técnicas e de design).</td>
    </tr>
    <tr>
      <td><strong>Professor/Orientador da PUC</strong></td>
      <td>Interno</td>
      <td>Acompanhar o desenvolvimento, avaliar a aplicação dos conceitos da disciplina, garantir a qualidade acadêmica.</td>
      <td>Alta (define os requisitos da avaliação e aprova as entregas).</td>
    </tr>
    <tr>
      <td><strong>Família do Usuário</strong></td>
      <td>Externo (Beneficiário)</td>
      <td>Beneficiam-se diretamente da boa gestão do orçamento familiar.</td>
      <td>Baixa (influência indireta, através da satisfação ou insatisfação do usuário principal).</td>
    </tr>
  </tbody>
</table>
