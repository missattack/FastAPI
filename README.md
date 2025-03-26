Esta API Python permite a inserção de informações para a aplicação Financeira, com método GET/POST e bibliotecas fastapi e uvicorn. 

<h1>Como executar?</h1>

Ao baixar a aplicação, ative o ambiente virtual a partir do terminal:
<h4>source .venv/bin/activate</h4>

A partir da pasta FastApi, execute o comando abaixo a fim de atualizar o arquivo main.py:
<h4>uvicorn main:app –-reload</h4>

Acesse o navegador com o endereço:  http://127.0.0.1:8000/docs. 

Serão apresentadas todas as rotas mapeadas. 

Método POST:

![image](https://github.com/user-attachments/assets/cf85496a-9cb7-4cec-8456-295a5118f1cc)
![image](https://github.com/user-attachments/assets/d98237fa-9a46-4cfc-8402-7162500f3067)

Método GET:

![image](https://github.com/user-attachments/assets/f760d86e-c8bd-4af5-95e1-7852b2571552)
![image](https://github.com/user-attachments/assets/ffed548d-f559-495e-a1a0-d912857351d3)

A interação visual é mediada pelo CORE middleware que conecta o front React à FastApi. Para isso, a partir do diretório REACT/FINANCE-APP digite o comando no terminal:

<h4>npm start</h4>

Abra o endereço http://localhost:3000 no navegador. Será apresentada a tela para lançamento das informações que alimentará a tabela localizada imediatamente abaixo dos campos:

![image](https://github.com/user-attachments/assets/32db1d2f-331a-4859-86f6-02a553c6af7a)
![image](https://github.com/user-attachments/assets/7b3f7268-7b53-4b10-83db-a641c050739d)










