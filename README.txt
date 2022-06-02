Projeto Suporte Tech Academy, criado para dar auxilio aos alunos que tenham
dúvidas nos modulos, quiz, projetos práticos.

Estrutura do projetos

index.html -> contendo todo o conteudo principal da Landing page, dividido em seções:

-> header inicial, onde se localiza o menu navegacional da página .

-> main é dividido em 4 seções:

1°- um article contendo o conteudo da apresentação princípal da página. 
2°- um article contendo o conteudo para os Cards das linguagens de front end e back end.
3°- um article contendo o conteudo para os Cards dos tutores.
4°- contendo o conteudo do footer.

Estruturas de CSS.. 

Usando CSS em modulo, cada seção com um modulo responsavel..

main.css -> Contém o menu navegacional, apresentação principal, e o footer..
OBS: index.html, sucesso.hmtl e suporte.html todos fazem o uso do "main.css"

cadrs.css -> Contém todos os cards usado na Landing page, usando como cards
padrão..
OBS: somente o index.html faz o uso do "cards.css"

suporte.css -> Contém todo o conteudo do formulário de envio..
OBS: somente suporte.html faz o uso do "suporte.html".

sucesso.css -> Contém todo o conteudo da página de sucesso quando o furmulario é enviado..
OBS: somente sucesso.html faz o uso do "sucesso.html".

Arquivos Javascript..

Temos o uso de 2 arquivos ..

1° - animate.js é usado para as animações, tanto para maquina de escrever, e fazer a chamada
da função usada com a Lib AOS..
OBS: usado no "index.html" e "sucesso.html".

2° - main.js é usado para a válidação de entrada do formulario...
OBS: usado somente "suporte.html". 

Blibliotecas usadas...

Lib AOS -> ele é usada para o efeito de scroll na seção dos dos Cards no "index.html".
OBS: usado somente na section dos Cards no index.html.

Lib Formsubmit.io -> é usada para o envio do formulario, sem precisa de um Back End..
OBS: usada somente no "suporte.html"


Link externo ..

-> Usando google font para padronizar o projeto somente com um modelo de letra...

Configuração do Formsubmit..

<form id="form" class="form" action="https://formsubmit.co/texstartse@gmail.com" method="POST">
"action configurando a url do formsubimt com o e-mail que deseja as mensagens ser enviadas pelo metodo POST".

<input type="hidden" name="_next" value="https://suporte-startse-tech-academy.vercel.app/sucesso.html">
"configurando para qual página você gostaria que fosse redirecionado caso o formulario tenha sucesso de envio".
OBS: sendo redirecionado para a pagina de sucesso onde irá redirecionar uma mensagem na tela.

<input type="hidden" name="_captcha" value="false">
"configurando para que não apareça um captcha para confirmar se você é um robo ou não antes do envio".

<input type="hidden" name="_autoresponse" 
value="Recebemos sua mensagem, obrigado pelo contato logo responderemos !">
"configurando para o usuário receber uma mensagem após o envio do formulario em seu e-mail".

