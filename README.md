

Bem-vindo ao projeto de previsão dos números vencedores da Mega Sena utilizando redes neurais LSTM! Este projeto tem como objetivo utilizar inteligência artificial para prever os números que serão sorteados na Mega Sena, com base em dados históricos dos sorteios anteriores.
Visão Geral:

A Mega Sena é uma das loterias mais populares do Brasil, e a capacidade de prever os números vencedores pode ser extremamente valiosa. Neste projeto, exploramos o uso de redes neurais LSTM, uma poderosa arquitetura de rede neural adequada para lidar com sequências temporais, para realizar essa tarefa desafiadora.
Funcionalidades:

    Carregamento de Dados: Os dados históricos da Mega Sena são carregados a partir de um arquivo CSV, contendo informações sobre os números sorteados em cada concurso.
    Pré-processamento de Dados: Os dados são pré-processados para garantir que estejam prontos para serem alimentados na rede neural. Isso inclui a remoção de colunas desnecessárias e a criação de janelas de histórico para cada entrada da rede.
    Treinamento da Rede Neural LSTM: Utilizando a biblioteca PyTorch, treinamos uma rede neural LSTM com os dados históricos da Mega Sena. Durante o treinamento, ajustamos os pesos da rede para minimizar a diferença entre as previsões e os números reais sorteados.
    Geração de Previsões: Após o treinamento, a rede neural é utilizada para gerar previsões para os próximos sorteios da Mega Sena. As previsões são processadas para evitar repetições de números.

Como Utilizar:

    Pré-requisitos:
        Certifique-se de ter Python instalado no seu ambiente.
        Instale as dependências necessárias, incluindo PyTorch, pandas, NumPy, scikit-learn e tqdm.

    Execução do Projeto:
        Execute os códigos disponíveis no ambiente de sua escolha (recomendamos Google Colab).
        Siga as instruções fornecidas nos códigos para carregar os dados, treinar o modelo e gerar previsões.

    Resultados:
        Ao final da execução, os resultados das previsões serão exibidos, incluindo as previsões processadas para os próximos sorteios da Mega Sena.

Contribuições:

Contribuições são bem-vindas! Se você tiver ideias para melhorar este projeto, sinta-se à vontade para abrir uma issue ou enviar um pull request. Juntos, podemos aprimorar ainda mais nossas habilidades em aprendizado de máquina e previsão de dados.
Licença:

Este projeto é licenciado sob a MIT License, o que significa que você pode utilizá-lo livremente e até mesmo modificar o código conforme suas necessidades. Agradecemos se você puder fornecer créditos ao projeto original ao utilizá-lo em seus próprios trabalhos.
