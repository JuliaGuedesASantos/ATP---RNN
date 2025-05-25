# <p align="center"> **Rede Neural Recorrente (RNN)** 🌠🌞 </p>
## <p align="center"> Utilizando uma Rede Neural Recorrente (RNN) para a previsão da quantidade diária de manchas solares </p>


**Autoras:** Júlia Guedes Almeida dos Santos & Eloísa Maria Amador Souza

**Disciplina:**  ATP-303 - Redes Neurais e Algoritmos Genéticos 

**Orientador:** Dr. Daniel Roberto Cassar

*** 
### Introdução 🖼️
<p align= "justify">
Recurrent Neural Networks (RNN), em português, Rede Neural Recorrente é um tipo de algoritmo utilizado para processar dados sequenciais. O diferencial das RNNs está no fato de que as informações dos inputs anteriores influenciam as entradas e saídas atuais. Assim, as RNNs possuem estados ocultos (ou hidden states) que funcionam como um memória em que as informações anteriores serão armazenadas. Dessa forma, a cada etapa, a RNN processa a entrada atual junto com o estado oculto da etapa anterior. Além disso, nesse tipo de rede também ocorre o compartilhamento de parêmetros entre as camadas, ou seja, utilizam o mesmo parâmetro de peso em todas as camadas. No entanto, esses são ajustados individualmente durante o processo de backpropagation e descida do gradiente para reduzir a perda.

Nesse sentido, o presente trabalho busca utilizar uma RNN para a previsão da quantidade diária de manchas solares, por meio do dataset "daily sunspots" da plataforma Kaggle. 
</p>


### Pré-requisitos 📄
<p align= "justify">
Para utilizar os notebooks presentes nesse repositório, é necessário ter conhecimentos prévios de Python e redes neurais - especialmente no que se refere a biblioteca Pytorch -, bem como utilizar um editor de códigos dessa linguagem. Em editores, como o Visual Studio Code (VS Code), é possível clonar o repositório para maior praticidade na obtenção dos arquivos. Nos demais casos, os arquivos podem ser baixados diretamente do repositório.
</p>

Para rodar os arquivos, além da utilização de versões mais atuais da linguagem Python (>=3.11), é preciso realizar a instalação das bibliotecas listadas abaixo nas seguintes versões:
```bash
pip install matplotlib==3.10.1
pip install numpy==1.26.4
pip install torch==2.5.1
pip install pandas==2.2.3
pip install scikit-learn==1.6.1
pip install seaborn==0.13.2
```

### Notebooks e demais arquivos 📓
Para a execução da tarefa proposta, os códigos foram feitos em um notebook: "4.8 - RNN para a previsão de manchas solares", o qual está contido no diretório principal do repósitório. Além disso, o arquivo zip contendo o dataset utilizado para o treinamento da rede (daily_sunspots-dataset.zip) também está postado. 

### Contribuidores 👥

| GitHub | Contribuições |
|:-----|:--------------|
| [Júlia Guedes A. dos Santos](https://github.com/JuliaGuedesASantos) | Implementação da rede neural, comentários no código e criação do repositório |
| [Eloísa Maria Amador Souza](https://github.com/Eloisa-Souza) | Implementação da rede neural e comentários no código |
| [Daniel Roberto Cassar](https://github.com/drcassar) | Orientador |

### Referências 📚
[1] SACHINSONI. Recurrent Neural Networks (RNN) from Basic to Advanced. Disponível em: <https://medium.com/@sachinsoni600517/recurrent-neural-networks-rnn-from-basic-to-advanced-1da22aafa009>. Acesso em: 18 abr. 2025.

[2] Implementing Recurrent Neural Networks in PyTorch. GeeksforGeeks. Disponível em: <https://www.geeksforgeeks.org/implementing-recurrent-neural-networks-in-pytorch/>. Acesso em: 18 abr. 2025.

[3] deep-learning-v2-pytorch/recurrent-neural-networks/time-series/Simple_RNN.ipynb at master · udacity/deep-learning-v2-pytorch. GitHub. Disponível em: <https://github.com/udacity/deep-learning-v2-pytorch/blob/master/recurrent-neural-networks/time-series/Simple_RNN.ipynb>. Acesso em: 18 abr. 2025.

[4] O que é uma Rede Neural Recorrente (RNN)? | IBM. Disponível em: <https://www.ibm.com/br-pt/think/topics/recurrent-neural-networks>. Acesso em: 15 maio 2025.

[5] SINGH, Rishabh. Recurrent Neural Network (RNN). Disponível em: <https://medium.com/@RobuRishabh/recurrent-neural-network-rnn-8412b9abd755>. Acesso em: 15 maio 2025.
