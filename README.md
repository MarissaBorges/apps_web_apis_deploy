<!-- PROJECT -->
<h1 align="center" style="font-weight: bold;">Portfólio de Aplicações Web com Python 🚀</h1>

<p align="center">
<!-- Adicione aqui os badges das tecnologias que você usou -->
<img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python Badge">
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit Badge">
<img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas Badge">
<img src="https://img.shields.io/badge/Spotify%20API-1ED760?style=for-the-badge&logo=spotify&logoColor=white" alt="Spotify API Badge">
<img src="https://img.shields.io/badge/OpenWeather%20API-EB6E4B?style=for-the-badge&logo=openweathermap&logoColor=white" alt="OpenWeather API Badge">
</p>

<p align="center">
  <a href="https://fifa-dep.streamlit.app/" target="_blank">
    <img src="https://img.shields.io/badge/Deployed%20on-Streamlit%20Cloud-FF4B4B?logo=streamlit&style=for-the-badge" alt="Deployed on Streamlit Cloud">
  </a>
</p>

<p align="center">
<a href="#-descrição">Descrição</a> •
<a href="#-funcionalidades">Funcionalidades</a> •
<a href="#-destaques-técnicos">Destaques</a> •
<a href="#-como-executar-localmente">Como Executar</a> •
<a href="#️-demonstrações-capturas-de-tela">Demonstrações</a> •
<a href="#-projetos-na-web">Projetos na Web</a>
</p>

---

## 📌 Descrição

Este repositório é um portfólio que reúne uma coleção de **aplicações web interativas** desenvolvidas com **Python** e a biblioteca **Streamlit**. O objetivo é demonstrar a criação de soluções práticas e elegantes que integram diferentes APIs para buscar e visualizar dados em tempo real. Cada projeto foi pensado para ser uma ferramenta útil e um exemplo claro do poder do Python no desenvolvimento web.

---

## 🚀 Funcionalidades

Este portfólio inclui os seguintes projetos:

- **Analisador de Nomes (IBGE):** Permite visualizar a popularidade de nomes no Brasil ao longo das décadas, consumindo a API pública do IBGE.
- **Previsão do Tempo (OpenWeather):** Consulta as condições climáticas atuais de qualquer cidade do mundo em tempo real.
- **Busca de Artistas (Spotify):** Pesquisa por artistas no Spotify e exibe informações detalhadas, como popularidade, seguidores e as 10 músicas mais tocadas.

---

## 🔒 Destaques Técnicos

- **Integração com APIs Externas:** Conexão e consumo de dados de três APIs distintas (IBGE, OpenWeather e Spotify), lidando com diferentes formatos de resposta.
- **Autenticação Segura:** Implementação do fluxo de autenticação **OAuth 2.0 (Client Credentials)** para garantir o acesso seguro à API do Spotify.
- **Desenvolvimento Rápido de UI:** Uso do Streamlit para construir interfaces de usuário interativas e responsivas com poucas linhas de código.
- **Visualização de Dados:** Criação de tabelas e gráficos dinâmicos com Pandas e Streamlit para apresentar os dados de forma clara e intuitiva.

---

## 📍 Como Executar Localmente

Siga as instruções abaixo para executar os projetos em seu ambiente local.

### Pré-requisitos

- [Python 3.8+](https://www.python.org/downloads/)
- [Git](https://git-scm.com/)

### Clonando o Repositório

```bash
# Clone o projeto para a sua máquina local
git clone https://github.com/MarissaBorges/apps_web_apis_deploy.git

# Entre no diretório do projeto
cd apps_web_apis_deploy
```

### Ambiente Virtual

É uma boa prática isolar as dependências do projeto.

```bash
# Crie o ambiente virtual
python -m venv .venv

# Ative o ambiente
# No Windows:
.venv\\Scripts\\activate

# No macOS/Linux:
source .venv/bin/activate
```

### Instale as Dependências

Com o ambiente virtual ativo, use o arquivo `requirements.txt` para instalar as dependências.

```bash
# Instale todas as bibliotecas necessárias
pip install -r requirements.txt
```

### Variáveis de Ambiente

Dois dos três projetos precisam de chaves de API para funcionar.
Obtenha em:

- **Open Weather:** [https://openweathermap.org/api](https://openweathermap.org/api)
- **Spotify:** [https://developer.spotify.com/dashboard/](https://developer.spotify.com/dashboard/)

> Crie um arquivo chamado `.env` na raiz do projeto e adicione as seguintes variáveis:

```yaml
# Chave para o projeto de previsão do tempo
CHAVE_API_OPEN_WEATHER="SUA_CHAVE_AQUI"

# Credenciais para o projeto de busca no Spotify
SPOTIFY_CLIENT_ID="SEU_CLIENT_ID_AQUI"
SPOTIFY_CLIENT_SECRET="SEU_CLIENT_SECRET_AQUI"
```

### Iniciando os Projetos

Cada aplicação é executada de forma independente.

```bash
# Para iniciar o Analisador de Nomes IBGE
streamlit run web_app_ibge.py

# Para iniciar o App de Previsão do Tempo
streamlit run web_app_open_weather.py

# Para iniciar a Busca de Artistas no Spotify
streamlit run web_app_spotify.py
```

### Como Interagir

- Após executar um dos comandos acima, uma aba será aberta no seu navegador.
- A interação é feita diretamente pela interface web, utilizando os campos de busca e botões.

---

## 🌐 Projetos na Web

Você pode acessar as aplicações diretamente nos links abaixo:

| Projeto                       | Link de Acesso                                                |
| ----------------------------- | ------------------------------------------------------------- |
| **Análise de Nomes IBGE**     | [Acessar Web App](https://web-app-api-ibge.streamlit.app/)    |
| **App de Previsão do Tempo**  | [Acessar Web App](https://web-app-openweather.streamlit.app/) |
| **Busca de Artistas Spotify** | [Acessar Web App](https://web-app-spotify.streamlit.app/)     |

---

## 🖼️ Demonstrações (capturas de tela)

### 📊 Web App IBGE

![Tela Inicial do App IBGE](https://i.postimg.cc/VLWnLqvt/image.png)
_Tela inicial da aplicação de análise de nomes._

![Tela de Pesquisa do App IBGE](https://i.postimg.cc/KYHwyH4f/image.png)
_Exibição da frequência do nome "Maria" ao longo das décadas._

---

### ☀️ Web App OpenWeather

![Tela Inicial do App OpenWeather](https://i.postimg.cc/1XCNWwv8/image.png)
_Interface inicial da aplicação de previsão do tempo._

![Tela de Pesquisa do App OpenWeather](https://i.postimg.cc/9fJnCFFy/image.png)
_Consulta das condições climáticas para a cidade de Goiânia._

---

### 🎵 Web App Spotify

![Tela Inicial do App Spotify](https://i.postimg.cc/t4ybgJyc/image.png)
_Tela inicial da ferramenta de busca de artistas no Spotify._

![Tela de Pesquisa de Artista no App Spotify](https://i.postimg.cc/76cDPNY1/image.png)
_Dashboard com informações detalhadas sobre o artista "Post Malone"._

![Tela de Pesquisa de Álbuns no App Spotify](https://i.postimg.cc/N0XjnM8f/image.png)
_Lista das 10 músicas mais populares do artista e sua respectiva popularidade._

---

## 🤝 Colaboradores

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/MarissaBorges">
        <img src="https://github.com/MarissaBorges.png?size=100" width="100px;" alt="Foto de Marissa Borges"/><br>
        <sub>
          <b>Marissa Borges</b>
        </sub>
      </a>
    </td>
  </tr>
</table>

---

## 📫 Como Contribuir

Contribuições são o que tornam a comunidade de código aberto um lugar incrível para aprender, inspirar e criar. Qualquer contribuição que você fizer será muito apreciada.

1.  Faça um **Fork** do projeto.
2.  Crie uma nova branch para sua Feature (`git checkout -b feature/AmazingFeature`).
3.  Faça o **Commit** de suas mudanças (`git commit -m 'Add some AmazingFeature'`).
4.  Faça o **Push** da sua branch (`git push origin feature/AmazingFeature`).
5.  Abra um **Pull Request**.

### Documentações Úteis

- [📝 Como criar um Pull Request](https://www.atlassian.com/br/git/tutorials/making-a-pull-request)
- [💾 Padrão de Commits (Conventional Commits)](https://www.conventionalcommits.org/en/v1.0.0/)
