Resumo da Aula

Estrutura Inicial

O aplicativo é composto por componentes principais como App.jsx, Header.jsx, Footer.jsx, Home.jsx, Destinos.jsx, e Contato.jsx, além de componentes específicos para destinos (Destino.jsx e FormDestino.jsx). O gerenciamento de estado utiliza useState para controlar a página atual e a lista de destinos. Na página inicial o usuário escolhe navegar entre as páginas Home, Destinos e Contato.

Regras de Negócio
1. Os cálculos de distância partem do Brasil.
2. 10 destinos pré-cadastrados com distâncias específicas.
3. Custos de voo baseados na distância: até 2000 km um voo (1500 reais), acima de 2000 km dois voos (3000 reais + 1 real por km adicional).
4. Custos variáveis de acordo com a data da viagem: menos de 2 meses (1500 reais), 2 meses ou mais (700 reais).
5. Estadia padrão (400 reais/semana) ou de luxo (700 reais/semana) com um acréscimo de 25% por participante adicional.

Cálculo de Distância e Custos

O cálculo é feito a partir das distâncias pré-cadastradas(que levam em consideração que os voos partem do Brasil), data de ida e volta, tipo de estalagem e número de participantes.
Esses cáculos são baseados nas regras de negócio 3,4 e 5. O subtotal é exibido em tempo real conforme o usuário ajusta as opções de viagem.

Interface de Seleção e Exibição do Subtotal

Os usuários selecionam destino, datas, tipo de estalagem e número de participantes, com o subtotal atualizado imediatamente. Após a seleção, são redirecionados para a tela de pagamento com opções de pix ou cartão de crédito.

Sugestões e melhorias

Incluir sugestões de destinos

Incluir a opção de filtar destinos por preço
