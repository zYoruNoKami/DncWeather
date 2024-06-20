Projeto: Aplicação Web de Consulta de Tempo e CEP

#Resumo

Este projeto é uma aplicação web interativa desenvolvida utilizando HTML5, CSS e JavaScript, que permite aos usuários consultar o tempo (condições meteorológicas) e obter informações detalhadas sobre um endereço a partir de um CEP fornecido. A aplicação faz uso de APIs externas para obter dados precisos e atualizados.

![image](https://github.com/zYoruNoKami/DncWeather/assets/116127722/4b8f0bf8-1f4c-49f3-8e1d-e1555d8b2cf0)

#Tecnologias Utilizadas

HTML5: Estrutura básica da aplicação, fornecendo uma marcação semântica e acessível.
CSS: Estilização da interface do usuário, garantindo um design responsivo e agradável visualmente.
JavaScript: Lógica de interação e manipulação de dados, incluindo a comunicação com APIs.
Funcionalidades

![image](https://github.com/zYoruNoKami/DncWeather/assets/116127722/947d2b09-cc98-4140-9971-4fc3f63c3f19)


#Consulta de Tempo:

Permite ao usuário inserir o nome de uma cidade ou coordenadas geográficas.
Utiliza uma API de serviço meteorológico (Open-Meteo) para buscar e exibir as condições atuais do tempo como temperatura.

![image](https://github.com/zYoruNoKami/DncWeather/assets/116127722/78912091-1d39-4e17-b8e0-b2aa69fe09f3)


#Consulta de CEP:

Permite ao usuário inserir um CEP (Código de Endereçamento Postal).
Utiliza uma API de serviço de CEP (como ViaCEP) para buscar e exibir informações detalhadas sobre o endereço correspondente ao CEP fornecido, incluindo rua, bairro, cidade e estado.

![image](https://github.com/zYoruNoKami/DncWeather/assets/116127722/2a9c6161-c3d8-4c46-a2bf-95c2bc95498f)


#Estrutura do Projeto

index.html: Contém a estrutura principal da página, com campos de entrada para o CEP e cidade, e áreas para exibição dos resultados.
styles.css: Define a aparência da aplicação, incluindo layouts, cores, fontes e estilos responsivos.
scripts.js: Contém a lógica de interação do usuário, incluindo chamadas às APIs e manipulação dos dados retornados.

![image](https://github.com/zYoruNoKami/DncWeather/assets/116127722/dfe5beeb-c0b1-4123-b2ca-a03e9f842e5c)


#Fluxo de Trabalho

Entrada de Dados:

O usuário insere o nome de uma cidade ou CEP no formulário da aplicação.

#Chamada à API:

Para a consulta de tempo, o JavaScript faz uma requisição à API meteorológica com o nome da cidade ou coordenadas.
Para a consulta de CEP, o JavaScript faz uma requisição à API de CEP com o código inserido.

#Processamento e Exibição:

Os dados retornados pelas APIs são processados e formatados.
As informações são exibidas de forma clara e organizada na página web, atualizando a interface de acordo com a entrada do usuário.

![image](https://github.com/zYoruNoKami/DncWeather/assets/116127722/525a8e71-e171-43eb-aa0f-e697fa2053b4)

#Conclusão

Este projeto exemplifica a criação de uma aplicação web moderna utilizando HTML5, CSS e JavaScript para oferecer uma experiência interativa aos usuários. Ao integrar APIs externas, a aplicação proporciona funcionalidades valiosas, como a consulta de condições meteorológicas e informações de endereços a partir de um CEP. 

Através do uso de APIs, o projeto demonstra a capacidade de se comunicar com serviços externos para obter e exibir dados em tempo real, aprimorando a funcionalidade e a usabilidade da aplicação. A aplicação de conceitos como a manipulação do DOM, requisições assíncronas e tratamento de respostas de APIs reflete as boas práticas de desenvolvimento web.

Além disso, o design responsivo e a estrutura semântica do HTML garantem acessibilidade e uma boa experiência do usuário em diversos dispositivos. Este projeto não só cumpre seu objetivo funcional de fornecer informações de tempo e CEP, mas também serve como uma base sólida para a construção de aplicações web mais complexas, destacando a importância da integração entre front-end e serviços web.

Em resumo, este projeto é um exemplo eficaz de como tecnologias web modernas podem ser combinadas para criar aplicações interativas, úteis e de alta performance, proporcionando aos desenvolvedores uma compreensão prática das possibilidades e técnicas disponíveis no desenvolvimento web contemporâneo.

Link do site disponibilizado:

Link da planilha de registro de informação: 
