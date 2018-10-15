# Devops-Teste

# 1 – O que são testes em DevOps?
# Testes e a ferramenta que fornece feedback continuo sobre os riscos do negocio.

# 2 – O que eles validam?
# Os testes visam validar se a aplicação esta funcionando corretamente e se atende aos requisitos especificados.

# 3 – Qual a diferença entre Verificação e Validação?
# Validaçao avalia um sistema ou componente para determinar se ele satisfaz os requisitos para ele especificado.
# Verificaçao avalia um sistema ou componente para determinar se os produtos de uma dada atividade de desenvolvimento satisfazem as condições impostas no inicio dessa atividade.

# 4 – Quais os objetivos do teste?
# Tem como objetivo revelar falhas e bugs para que sejam corrigidas ate que o produto final atinja a qualidade desejada/acordada.

# 5 – O que é um Test Case?
# Caso de teste é um conjunto de condições usadas para teste de software. Ele pode ser elaborado para identificar defeitos na estrutura interna do software por meio de situações que exercitem adequadamente todas as estruturas utilizadas na codificação; ou ainda, garantir que os requisitos do software que foi construído sejam plenamente atendidos.

# 6 – O que é um Test Suite?
# Conjunto de testes , menos conhecido como "conjunto de validação&quot, é uma coleção de casos de teste que devem ser usados ​​para testar um programa de software para mostrar que ele possui alguns conjuntos de comportamentos especificados. Um conjunto de testes geralmente contém instruções detalhadas ou metas para cada coleção de casos de teste e informações sobre a configuração do sistema a ser usada durante o teste. Um grupo de casos de teste também pode conter estados ou etapas de pré-requisitos e descrições dos testes a seguir.

# 7 – Quais são os tipos de teste?
# Os 13 principais tipos de testes
# 1. Teste de Configuração
# 2. Teste de Instalação
# 3. Teste de Integridade
# 4. Teste de Segurança
# 5. Teste Funcional
# 6. Teste de Unidade
# 7. Teste de Integração
# 8. Teste de Volume
# 9. Teste de Performance
# 10. Teste de Usabilidade
# 11. Testes de Caixa Branca e Caixa Preta
# 12. Teste de Regressão
# 13. Teste de Manutenção

# 8 – O que são testes do tipo Caixa Branca e Caixa Preta?
# Teste caixa-branca (ou Teste Estrutural)
# Técnica de teste que avalia o comportamento interno do componente de software. Trabalha diretamente sobre o código-fonte do componente de software para avaliar aspectos tais como: teste de condição, teste de fluxo de dados, teste de ciclos e teste de caminhos lógicos. O testador tem acesso ao código fonte da aplicação e pode construir códigos para efetuar a ligação de bibliotecas e componentes. Exemplo: uso da ferramenta livre JUnit para desenvolvimento de casos de teste para avaliar classes ou métodos desenvolvidos na linguagem Java.
# Teste caixa-preta (ou Teste Funcional)
# Técnica de teste em que o componente de software a ser testado é abordado como se fosse uma caixa-preta, ou seja, não se considera o comportamento interno do mesmo. Dados de entrada são fornecidos, o teste é executado e o resultado obtido é comparado a um resultado esperado previamente conhecido. Haverá sucesso no teste se o resultado obtido for igual ao resultado esperado. O componente de software a ser testado pode ser um método, uma função interna, um programa, um componente, um conjunto de programas e/ou componentes ou mesmo uma funcionalidade.

# 9 – Procure o que é o diagrama da pirâmide de teste, e a sua relação com o
# custo. Reproduza o diagrama com comentário.
# A Piramide de teste é um guia que serve para dizer o quanto de teste sera necessario para cada camada de teste, as camadas de testes sao compostas normalmente por aceitação, integracao e unidade.
# A piramide ela tem a ideia de ter uma restrição baseada na atureza dos seus testes, os testes que sao mais lentos e mais frageis tem menos testes, pois sao mais pesados de serem realizados e com isso mais lentos.
# Falando um pouco das camadas da Piramide
# Camada de aceitação:
# Na camada de aceitação sao realizados menos testes pois sao testes mais lentos e mais frageis.
# Camada de Integração:
# Ja na camada de Integração que sao testes mais rapidos e menos frageis que na camade de aceitação sao realizados mais testes.
# Camada de Unidade:
# ja na camada de unidade que sao testes leves onde consiste em validar dados validos e invalidos via entrada e saida é a parte da piramide onde é concentrada a maior parte dos testes
# A relação da Piramide com o custo é que como o tester esta fazendo testes sobre camadas ele sabera aonde exatamente esta o problema e com isso ganha tempo no momento de acertar o programa.
# Reproduzindo o diagrama:
# Camada de Aceitação -
# Testes mais lentos, frageis e complexos de escrever.
# Camada de Integração -
# O que foge do Escopo do teste de unidade mas nao chega no teste de aceitação, exemplo testes de api ou testes de integração
# Camada de Unidade -
# Testes "FACEIS" e rapidos de serem executados, indicam Exatamente ou quase onde esta o erro, garantem integridade das menores "peças" do sistema

# 10 – Percentualmente, qual é a distribuição dos tipos de testes na pirâmide de testes?
# 70% de testes unitários
# 20% de testes de integração
# 10% de testes de ponta a ponta
