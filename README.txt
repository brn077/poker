POKER OSASCO — SISTEMA TV + ADM

ARQUITETURA
- display.html = tela limpa para a TV. Não há edição nela.
- admin.html = painel de controle para computador/celular.
- config.js = configuração do Firebase Realtime Database.
- A TV e o ADM sincronizam em tempo real pelo Firebase.

PUBLICAÇÃO
1. Coloque display.html, admin.html e config.js no mesmo diretório do seu site.
2. Crie um projeto no Firebase.
3. Ative Realtime Database.
4. Crie um Web App e copie o firebaseConfig para config.js.
5. Configure as regras do Realtime Database de acordo com sua política de segurança.
6. Abra /display.html na TV.
7. Abra /admin.html no computador/celular do operador.

OBSERVAÇÃO
O sistema foi desenhado para a TV ter apenas a apresentação. O ADM fica totalmente separado.
Para uso real em produção, recomendo proteger o admin com autenticação e regras do Firebase.
