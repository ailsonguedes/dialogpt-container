# DialoGPT: Microsoft DialogGPT + Docker

Esse código foi desenvolvido como um estudo utilizando o Microsoft DialogGPT-Large que pode ser encontrado no site 🤗[Hugging Face](https://huggingface.co/microsoft/DialoGPT-large?text=Hey+my+name+is+Julien%21+How+are+you%3F), também foi utilizado o 🐋[Docker](https://docs.docker.com/get-started/) para containerizar a aplicação. 


## 🔧 Ferramentas Utilizadas

- [Docker](https://docs.docker.com/get-started/): Uma plataforma de contêineres que permite que os desenvolvedores empacotem seus aplicativos em contêineres portáteis, que podem ser executados em qualquer ambiente. Isso torna a implantação e execução de aplicativos mais fáceis e eficientes, pois as dependências e o ambiente de execução são encapsulados no contêiner..
- [Pytorch](https://pytorch.org/): Uma biblioteca de aprendizado de máquina de código aberto para Python, que fornece uma estrutura flexível e eficiente para a criação de redes neurais e a realização de computação numérica usando GPUs.
- [Transformers](https://huggingface.co/docs/transformers/index): Uma biblioteca de código aberto desenvolvida pela Hugging Face, que oferece uma interface fácil de usar para trabalhar com modelos de linguagem pré-treinados, especialmente em tarefas relacionadas ao processamento de linguagem natural (NLP).

## ⚙️ Como Funciona

- Antes de executar o código, certifique-se de ter o Docker instalado em sua máquina.
- Este aplicativo apresenta uma IA que conversa com o usuário por meio de um chat no prompt de comando.

## 💻 Como executar o código

- Instalar Docker
- Abra o prompt de comando
- Navegue até a pasta raiz do projeto, onde estão localizados os arquivos "dialogpt_script.py", "requirements.txt" e "Dockerfile".
- Primeiramente, crie uma imagem Docker a partir do Dockerfile utilizando o seguinte comando: **docker build -t dialogpt-container**.
- Para executar o aplicativo, utilize o comando: **docker run -it dialogpt-container**.
