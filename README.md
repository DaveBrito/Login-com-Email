# Login + Autenticação 

Projeto tem o objetivo do usuário criar uma conta, trocar sua senha e adicionar um novo usuário.

Sendo feito e designado para a disciplina de `Programação para Dispositivos Moveis I` , com orientações do professor  
`Paulo Rogerio da Silva`.

# Ferramenta

- Usado o Android Studio para desenvolvimento
- Implementação do [Firebase](https://firebase.google.com/?hl=pt-br) para autenticação com a conta.

# Possíveis Problemas no Desenvolvimento
- Como no Android Studio não temos a função `run gradle signingReport`, na atual versão, 2023.2.1, é necessário ativar pelo terminal o comando.

```bash
./gradlew signingReport
```
Será exibido um erro sobre o comando, posteriomente escreva-o novamente mas com o mouse em cima, aperte `Ctrl` + `Enter` que irá funcionar para conseguir o `SHA1`.

```bash
> Task :app:signingReport
Variant: debug
Config: debug
Store: /path/to/debug.keystore
Alias: AndroidDebugKey
MD5: A1:B2:C3:D4:E5:F6:G7:H8:I9:J0:K1:L2:M3:N4:O5:P6:Q7:R8
SHA1: AB:CD:EF:12:34:56:78:90:12:34:56:78:90:12:34:56:78:90:12:34
SHA-256: 12:34:56:78:90:12:34:56:78:90:12:34:56:78:90:12:34:56:78:90:12:34:56:78:90:12:34:56:78:90:12:34
Valid until: Monday, January 1, 2050

BUILD SUCCESSFUL in 2s
1 actionable task: 1 executed



```
