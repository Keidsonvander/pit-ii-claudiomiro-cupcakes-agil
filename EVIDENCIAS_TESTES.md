# Evidências dos Testes e Correções — PIT II

**Aluno:** Claudiomiro Monteiro Junior  
**RGM:** 33634254  
**Projeto:** Aplicativo de vendas online para loja de cupcakes gourmet  
**Data dos testes:** 17/11/2026

## Participantes
- Felipe Augusto Nunes
- Patrícia Gomes de Oliveira
- Vinicius Roberto Almeida
- Juliana Cristina Barbosa
- Rafael Henrique Moreira

## 1. Mensagem de confirmação do carrinho
**Problema identificado:** a mensagem apresentada após adicionar um produto possuía pouco destaque visual.

**Correção aplicada:** foram criadas mensagens específicas para sucesso e erro, com maior contraste e texto mais claro.

**Evidência:** classes `msg ok` e `msg erro` e função `mensagem()` adicionadas ao arquivo `index.html`.

## 2. Validação dos campos obrigatórios
**Problema identificado:** a orientação apresentada ao deixar informações obrigatórias em branco era pouco específica.

**Correção aplicada:** o sistema passou a verificar nome, telefone, endereço, pagamento e entrega, informando quais campos precisam ser preenchidos.

**Evidência:** nova lógica de validação inserida na finalização do formulário.

## 3. Destaque da etapa atual
**Problema identificado:** a situação atual do pedido não possuía destaque suficiente.

**Correção aplicada:** a etapa “Pedido recebido” passou a receber destaque visual e a indicação “atual”.

**Evidência:** atualização do componente de acompanhamento no `index.html`.

## 4. Responsividade
**Problema identificado:** alguns campos e botões apresentavam pouco espaçamento em telas menores.

**Correção aplicada:** foram ampliados os espaçamentos, áreas de interação e organização dos componentes em smartphones.

**Evidência:** novas regras inseridas no media query para telas de até 600 pixels.

## 5. Confirmação final
**Problema identificado:** a confirmação final apresentava poucas informações.

**Correção aplicada:** foi incluído um resumo com número do pedido, nome do cliente, forma de pagamento, modalidade de entrega e status atual.

**Evidência:** novo bloco `confirmacao` adicionado à interface.

## Nova verificação
Após as correções, foram revistos catálogo, carrinho, mensagens, validações, pagamento, entrega, acompanhamento, confirmação final e responsividade. O fluxo principal apresentou funcionamento satisfatório após os ajustes.

## Funcionalidades previstas para evolução futura
- cadastro e autenticação de usuários;
- processamento real de pagamentos;
- rastreamento em tempo real;
- histórico de pedidos;
- área administrativa;
- testes em uma variedade maior de dispositivos e navegadores.
