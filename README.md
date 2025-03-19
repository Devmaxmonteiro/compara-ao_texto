📌 Documentação do Sistema de Comparador de Textos com IA
Este projeto é um sistema de comparação de textos utilizando Flask e a API do DeepSeek para realizar análise de diferenças entre textos. Ele permite que os usuários insiram dois textos e obtenham uma análise das diferenças entre eles.
________________________________________
🚀 Tecnologias Utilizadas
•	Python: Linguagem principal do sistema
•	Flask: Framework web para criar a aplicação
•	HTML/CSS: Para a interface da aplicação
•	DeepSeek API: Para realizar a comparação e análise dos textos
•	Bootstrap: Para estilização da interface
________________________________________
📂 Estrutura do Projeto
compara_textos/
│-- templates/
│   │-- index.html   # Interface web
│-- static/
│   │-- styles.css   # Estilos CSS (opcional)
│-- app.py          # Arquivo principal do Flask
│-- requirements.txt # Dependências do projeto
│-- README.md       # Documentação do projeto
________________________________________
⚙️ Instalação e Execução
1️⃣ Clonar o Repositório
git clone https://github.com/seu-usuario/compara-textos-flask.git
cd compara-textos-flask
2️⃣ Criar Ambiente Virtual
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate  # Windows
3️⃣ Instalar Dependências
pip install -r requirements.txt
4️⃣ Configurar a Chave de API
Crie um arquivo .env na raiz do projeto e adicione sua chave da API do DeepSeek:
DEEPSEEK_API_KEY="sua-chave-aqui"
5️⃣ Executar o Servidor
python app.py
Acesse a aplicação no navegador em:
http://127.0.0.1:5000
________________________________________
🖥️ Uso da Aplicação
1.	Acesse a interface web.
2.	Insira dois textos nos campos de entrada.
3.	Clique no botão Comparar.
4.	O sistema irá exibir as diferenças entre os textos usando IA.
________________________________________
📜 Licença
Este projeto está licenciado sob a MIT License.
Sinta-se à vontade para contribuir, melhorar ou utilizar para seus propósitos! 😊

