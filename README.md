# Documentação dos Avanços no Desenvolvimento 

No início, o projeto consistia apenas no conceito de como aplicar ML e IA para análise de imagens dentárias.  Algumas ideias estavam em mente, como a utilização de modelos de Deep Learning (como PyTorch) e ferramentas de manipulação e análise de dados tabulares (como o Pandas). Com o tempo, conseguimos transformar o conceito inicial em um modelo funcional.  

Utilizamos da plataforma Roboflow para criar e anotar um conjunto de dados robusto, com um dataset composto por mais de 2.000 imagens de dentes e com 6 classes anotadas. As classes incluem condições como cáries e tártaro, com uma variedade de imagens de dentes saudáveis e com problemas dentários. Esse processo de anotação foi essencial para treinar o modelo de forma eficiente. Optamos por utilizar a API do Roboflow para facilitar os processos de criação, treinamento e inferência, o que nos permitiu realizar previsões de forma rápida e acessível. Durante a fase de treinamento, realizamos ajustes nos parâmetros do modelo e aplicamos técnicas de data augmentation para melhorar a generalização do modelo. 

![Captura de tela 2025-03-20 230102](https://github.com/user-attachments/assets/d0ebaf1b-70bd-4e02-8444-e2b17703c574)

Dentro do notebook do Colab fizemos uso da biblioteca Matplotlib para visualização da predição realizada na imagem e mostrar a detecção das condições dentárias presentes na foto.

Hoje, temos um modelo funcional que já é capaz de analisar imagens dentárias e identificar algumas das condições. Embora o modelo ainda não esteja 100% preciso, ele já apresenta bons resultados em imagens de teste, sendo capaz de detectar e classificar corretamente várias condições dentárias. 

 

# Conclusão 

O projeto evoluiu de um simples conceito de aplicação de IA e ML para um modelo funcional que já realiza a detecção de doenças dentárias com base em imagens, conseguimos dar passos significativos em direção à automação da análise de condições dentárias. Embora o modelo ainda precise de ajustes e melhorias, os avanços até agora são promissores e estamos confiantes de que, com mais dados e treinamento, o modelo será cada vez mais eficaz. 


# Próximos Passos

No futuro esperamos tornar o modelo ainda mais preciso, porem nossa prioridade agora será realizar a implementação da IA dentro do aplicativo Oralytics.

![Captura de tela 2025-03-20 223202](https://github.com/user-attachments/assets/6372b278-f141-4f78-b235-27ebf9437aeb)


### Link do vídeo demonstrativo de nossa IA: 

https://youtu.be/ux-eOPWRHY0

### Projeto desenvolvido por:
- Gabriel Grego
- André Alves
- Kayque Ferreira
