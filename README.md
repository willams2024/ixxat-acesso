# ixxat-acesso

Arquivo de senha do **IxxatInterface v7**, publicado por `definir_senha.py`.

`senha.json` contém só a **impressão digital** da senha de acesso
(PBKDF2-HMAC-SHA256, 600 mil iterações) e uma **assinatura Ed25519**. O
programa só aceita o arquivo se a assinatura conferir com a chave pública
embutida nele: editar o arquivo à mão o invalida.

Não apague este repositório nem o torne privado: os programas baixam a senha
daqui. Sem conseguir baixar, cada cópia funciona por até 48 h com a última
senha baixada e depois para de abrir.
