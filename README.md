# Login + Autenticação 

Projeto tem o objetivo do usuário criar uma conta, trocar sua senha e adicionar um novo usuário.

# Ferramenta

- Usadoo Android Studio para desenvolvimento,mais a implementação do Firebase para autenticação.

# Possíveis Problemas
- Como no Android Studio não temos a função `run gradle signingReport`, é necessário ativar pelo terminal.

```bash
./gradlew signingReport
```
Posterimente, escreva novamente mas com o mouse em cima, aperte `Ctrl` + `Enter` que irá funcionar para conseguir o `SHA1`.

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
