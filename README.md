### 📊 Análise de Nomes no Brasil com Python e Streamlit

🔗 **Link do Projeto na Web**: [Analisador de Nomes IBGE](https://web-app-ibge.streamlit.app/)

#### 📌 Descrição

O **Analisador de Nomes IBGE** é uma aplicação web interativa desenvolvida para visualizar a popularidade de nomes no Brasil ao longo das décadas. A ferramenta consome a API pública de Nomes do **IBGE** e apresenta a frequência de um determinado nome em uma tabela e em um gráfico de linha, permitindo uma análise clara de sua evolução temporal.

Construído com **Python** e **Streamlit**, o projeto oferece uma interface simples onde o usuário insere um nome e recebe instantaneamente a análise visual e numérica dos dados, tornando fácil a exploração de tendências de nomes no país.

---

#### 🚀 Funcionalidades

- **Consulta Dinâmica:** Busque qualquer nome e veja sua frequência histórica em tempo real.
- **Tabela de Frequência:** Exibe os dados brutos de frequência para cada década de forma organizada.
- **Gráfico de Evolução:** Plota um gráfico de linhas que ilustra a ascensão ou queda da popularidade do nome.
- **Integração com API do IBGE:** Garante que os dados sejam confiáveis e diretamente extraídos da fonte oficial.

---

#### 🛠️ Tecnologias Utilizadas

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

---

#### 🏃 Como Executar

1.  **Clone o Repositório:**

    - Abra o seu terminal e clone este projeto para a sua máquina local.

    ```bash
    git clone https://github.com/MarissaBorges/app_ibge_deploy.git
    ```

2.  **Acesse a Pasta do Projeto:**

    ```bash
    cd app_ibge_deploy
    ```

3.  **Crie e Ative um Ambiente Virtual (Recomendado):**

    - Isso isola as dependências do projeto.

    ```bash
    # Para Windows
    python -m venv venv
    .\\venv\\Scripts\\activate

    # Para macOS/Linux
    python3 -m venv venv
    source venv/bin/activate
    ```

4.  **Instale as Dependências:**

    - As bibliotecas necessárias estão listadas no arquivo `requirements.txt`. Instale-as com o comando:

    ```bash
    pip install -r requirements.txt
    ```

5.  **Execute a Aplicação:**
    - Com tudo instalado, inicie o servidor do Streamlit:
    ```bash
    streamlit run app.py
    ```
    - A aplicação será aberta automaticamente no seu navegador padrão.

---

#### 🔒 Destaques Técnicos

- 🔌 **Consumo de API REST:** Conecta-se diretamente à API do IBGE para buscar dados de forma eficiente.
- 🔄 **Manipulação de Dados:** Utiliza a biblioteca **Pandas** para transformar os dados JSON da API em um DataFrame estruturado.
- 🎨 **Interface Reativa:** A interface, construída com **Streamlit**, reage instantaneamente à entrada do usuário sem a necessidade de recarregar a página.
- 📈 **Visualização de Dados:** Geração automática de tabelas e gráficos para uma interpretação clara e imediata dos resultados.

---

#### 🖼️ Demonstrações (capturas de tela)

- Página Inicial da Aplicação
![Página Inicial da Aplicação](https://i.postimg.cc/VLWnLqvt/image.png)

- Resultado da Consulta por um Nome
![Resultado da Consulta por um Nome](https://i.postimg.cc/rFVzjvyd/image.png)

- Tratamento de erros para nomes inexistentes
![Tratamento de erros para nomes inexistentes](https://i.postimg.cc/tJ2q84Rs/image.png)
