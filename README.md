Protótipo Flask + SQLAlchemy + Bootstrap

Instruções rápidas:

1) Crie e ative um virtualenv (opcional mas recomendado):

   python3 -m venv venv
   source venv/bin/activate

2) Instale dependências:

   pip install -r requirements.txt

3) Crie o banco e usuários de teste:

   python createdb.py
   python init_db.py

4) Rode a aplicação:

   python run.py

Acesse http://127.0.0.1:5000/ e use os usuários de teste listados no script `init_db.py`.
