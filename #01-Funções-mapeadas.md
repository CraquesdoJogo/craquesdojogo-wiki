* Organizador \[M1\]
  * Criar conta \[M1-F1\] / Editar \[M1-F2\] / Desabilitar \[M1-F3\]
  * Alterar senha \[M1-F4\] / Confirmar E-mail \[M1-F5\] / Definidir arroba da conta \[M1-F6\]
  * Vincular com: Quadras / Times / Torneios
  * **Funções:** 6
* Admin \[M2\]
  * Adicionar \[M2-F1\] / Editar \[M2-F2\] / Desabilitar \[M2-F3\]
  * Alterar senha \[M2-F4\]
  * **Funções:** 4
* Apostador/Usuário \[M3\]
  * Criar conta \[M3-F1\] / Editar \[M3-F2\] / Desabilitar \[M3-F3\]
  * Alterar senha \[M3-F4\] / Confirmar E-mail \[M3-F5\] / Definidir arroba da conta \[M3-F6\]
  * Vincular com: Jogador(para administrar) / Apostas /
  * **Funções:** 6
* Jogador \[M4\]
  * Adicionar \[M4-F1\] / Editar \[M4-F2\] / Desabilitar \[M4-F3\]
  * Atribuir usuário \[M1-F4\] / Definidir arroba da conta \[M1-F5\]
  * Vinculado com: Gols / Times / Usuário
  * **Funções:** 5
* Quadras \[M5\]
  * Adicionar \[M5-F1\] / Editar \[M5-F2\] / Desabilitar \[M5-F3\]
  * Atribuir time da casa \[M5-F4\]
  * Vinculado com: Time
  * **Funções:** 4
* Torneios \[M6\]
  * Adicionar \[M6-F1\] / Editar \[M6-F2\] / Desabilitar \[M6-F3\]
  * Adicionar Jogo \[M6-F4\] / Remover Jogo \[M6-F5\]
  * Vinculado com: Jogos
  * **Funções:** 5
* Jogos \[M7\]
  * Adicionar \[M7-F1\] / Editar\[M7-F2\] / Desabilitar \[M7-F3\]
  * Vincular gol \[M7-F4\] / Remover Gol \[M7-F5\] / Encerrar Jogo \[M7-F6\]
  * Desafio(Fazer/se candidatar/aceitar)
  * Vinculado com: Quadra / Times / Gols
  * **Funções:** 6
* Planos \[M8\]
  * Adicionar \[M8-F1\] / Editar \[M8-F2\] / Desabilitar \[M8-F3\]
  * Contratar \[M8-F4\] / Cancelar \[M8-F5\]
  * Vincluar com: Usuário / Faturas / Pagamentos
  * **Funções:** 5
* Gols \[M9\]
  * Vinculado com: Jogador / Time / Jogo / Quadra / Torneio
* Times \[M10\]
  * Criar time \[M10-F1\] / Editar Time (Brazão ou logo, fotos de capa e perfil, nome do time, etc) \[M10-F2\] / Desabilitar Time \[M10-F3\]
  * Atribuir Jogador com posição \[M10-F4\] / Remover Jogadores \[M10-F5\] / Definir Capitão \[M10-F6\]
  * Definidir arroba da conta \[M10-F7\]
  * Vinculado com: Jogadores / Organizador / Quadra
  * **Funções:** 6
* Faturas \[M11\]
  * Gerar Fatura para pagamento \[M11-F1\]
  * Vinculado com: Pagamentos / Usuário / Planos / Carteira
  * **Funções:** 1
* Pagamentos \[M12\]
  * Pagar \[M12-F1\]
  * Vinculado com: Faturas
  * **Funções:** 1
* Carteira \[M13\]
  * Carregar(Gera fatura) \[M13-F1\] / Saque no stripe \[M13-F2\]
  * Vinculado com: Usuário
  * **Funções:** 2
* Cartiera Fake \[M14\]
  * Recarregar: \[M14-F1\]
  * Vinculado com: Usuário
  * **Funções:** 1
* Chat Grupo \[M15\]
  * Vinculado com: Time / Usuários
* Chat Mensagem \[M16\]
  * Enviar mensagem \[M16-F1\] / Enviar Foto \[M16-F2\] / Enviar Video \[M16-F3\]
  * Vinculado com: Chat / Usuário
  * **Funções:** 3
* Aposta \[M17\]
  * Lançar aposta \[M17-F1\] / Cobrar Aposta \[M17-F2\]
  * Vinculado com: Jogo / Usuários / Time
  * **Funções:** 2
* Aposta Fake \[M18\]
  * Lançar apostar \[M18-F1\] / Cobrar Apostar \[M18-F2\]
  * Vinculado com: Jogo / Usuários / Time
  * **Funções:** 2
* API Stripe \[M19\]
  * Conctar conta de apostador \[M19-F1\] / Conectar conta principal \[M19-F2\] / Assinatura \[M19-F2\] / Recebimento \[M19-F3\]
  * Módulo de conexão com o stripe
  * **Funções:** 3
* API ManyChat e notificaçẽos \[M20\]
  * Enviar notificação gol \[M20-F1\] / Enviar notificação Jogo começando \[M20-F2\] / Enviar notificação resumo final do jogo \[M20-F3\]
  * Módulo de conexão com o Manychat
  * **Funções:** 3
* Social - Postagem (foto/video/texto) com sistema de Arrobas \[M21\]
  * Enviar mensagem \[M21-F1\] / Enviar Foto \[M21-F2\] / Enviar Video \[M21-F3\]
  * Excluir publicação \[M21-F4\] / Editar mensagem \[M21-F5\]
  * Vinculado com: Usuário / (time/usuário via arroba)
  * **Funções:** 5
* Social - Curtidas \[M22\]
  * Curtir \[M22-F1\] / Remover curtida \[M22-F2\]
  * Vinculado com: Postagem / Comentário / Usuário
  * **Funções:** 2
* Social - Comentários \[M23\]
  * Comentário \[M23-F1\] / Editar Comentárior \[M23-F2\] / Remover Comentárior \[M23-F3\]
  * Vinculado com: Postagem / Usuário / (time/usuário via arroba)
  * **Funções:** 3
* Idiomas \[M24\]
  * Visualizar texto em diferentes idiomas cadastrados, será feito a configuração na inicialização