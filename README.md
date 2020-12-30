# blog
Blog desenvolvido em django, biblioteca de desenvolvimento web em python.
O presente trabalho tratou da elaboração em python de um projeto de desenvolvimento web utilizando para o objetivo
a biblioteca django. O projeto trata-se de um BLOG de posts. Foi utilizado tanto
o método de funções como o método de Class Based View (CBV) para o desenvolvimento das rotinas. Para o teste foi coletado
dados randômicos, inseridos manualmente, para depois ser estudado o comportamento da máquina e seus possiveis problemas. Além disso, foi criado um ambiente
virtual a partir do próprio python pelo cmd do windows. Os arquivos estáticos também estão disponiveis para teste.

(lembrando que é necessário instalar o python primeiro)

# Ambiente Virtual

Para criar o ambiente virtual em sua máquina windows (e assim poder rodar o projeto da mesma maneira que eu fiz), basta entrar no cmd e digitar...

`py -m pip --version`

Para atualizar o pip, depois;

`py -m pip install --user virtualenv`

Para instalar um ambiente virtual, depois;

`py -m venv env`

Para criar uma máquina virtual. Pronto, máquina virtual criada!

# Ativando a máquina virtual

`.\env\Scripts\activate`

Vá para a pasta Scripts e ative a máquina, no fechamento do projeto não esqueça de desativar (fazendo o mesmo processo e digitando "deactivate" ao invés de "activate")

# Para criar um usuário (e ter acesso ao sistema) basta digitar;

`python manage.py createsuperuser`

e assim seguirá os passos para criar uma conta, depois basta repetir o nome de usuário antes do @ do seu email e a senha.

# Rodando a máquina

Com a máquina criada basta voltar para o nível da pasta do projeto e depois digitar;

`python manage.py makemigrations`

`python manage.py migrate`

`python manage.py runserver`


Copie em seu navegador o endereço https criado e aproveite!
