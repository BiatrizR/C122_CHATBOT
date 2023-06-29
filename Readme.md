#first steps
 - criar ambiente pytho
    - python -m venv nomedoprojeto

 - navegar para o ambiente e  ativar ambiente
    - use o cmd
    -nomedoprojeto\Scripts\activate

- instalar o flask
    - pip install flask
    - pip install tensorflow
    - pip install nltk
    - pip intall pandas
- navegar
    -cd noemdoprojeto

## 
*A chamada AJAX para exibir datas, prever emoções e salvar a entrada do diário foi fornecida no arquivo index.js. Em seguida, teremos que escrever a chamada AJAX para enviar mensagens e receber respostas do chatbot.*

## Para a chamada AJAX usaremos os seguintes passos:
1. Escreva o tipo de requisição que estamos enviando para a API. Será o método "POST".
2. Defina uma URL para receber a resposta do robô.
3. Escreva o método stringify para enviar os dados no formato JSON.
4. Escreva o tipo de dados que estamos enviando(JSON).
5. Defina o tipo de conteúdo como ‘application/json’;
6. Na função success, a resposta do chatbot deve ser exibida para cada mensagem do usuário.
7. Para cada mensagem do usuário, anexe a resposta do robô, que é o resultado que obteremos da API. Vamos chamá-la de bot_response.
8. Então, na div messages, anexe bot_response.
9. Para tornar o chatbot rolável para ler as mensagens anteriores, use a função scrollTop(). Nesta função, selecione o elemento que deve ser rolável e a altura da área rolável; 
10. Se houver algum erro, escreva o método error que exibirá uma caixa de diálogo com a mensagem deerro.
11. Se a tecla Enter for pressionada, o botão enviar deve ser ativado.
12. Selecione então o bot_input_text para o evento keypress. O botão Enviar deve ser clicado.
13. O código da tecla Enter é 13. Então use o parâmetro e.which para comparar com o valor da tecla.

# USANDO APPEND:
 lista = ["pao", "leite"]
>>> lista.append("suco")
>>> print(lista)
['pao', 'leite', 'suco']

>>> segundaLista =["moeda", 2]
>>> lista.append(segundaLista)
>>> print(lista)

['pao', 'leite', 'suco', ['moeda', 2]]