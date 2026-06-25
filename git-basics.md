### Aprendi sobre :
# O ciclo de vida de um ficheiro no Git
Esta é, na minha opinião, a aula mais importante de todo o Git.
Imagina que crias um ficheiro:


( calculadora.py )

Quando trabalhas com Git, esse ficheiro passa por 4 estados:

### 🆕 Novo
    ↓
### 📋 Preparado (Staged)
    ↓
### 📸 Commit
    ↓
### ☁️ GitHub


# Entendendo cada um deles.

### 🆕 Estado 1 — Novo (Untracked)
Acabaste de criar:

( calculadora.py )

O Git diz:
"Vejo este ficheiro, mas ainda não estou a controlá-lo."
É como um aluno novo que entrou na escola mas ainda não foi registado.

### 📋 Estado 2 — Preparado (Staged)
Agora dizes ao Git:
"Quero guardar este ficheiro no próximo commit.":

( git add calculadora.py )

Ou, para todos os ficheiros:

( git add . )

O git add não guarda o ficheiro. Apenas diz ao Git que ele deve entrar na próxima "fotografia".

### 📸 Estado 3 — Commit

Agora tiras a fotografia do projeto:

( git commit -m "Adiciona calculadora" )
A partir daqui, essa versão fica registada no histórico.

### ☁️ Estado 4 — GitHub
Por fim, envias tudo para o GitHub:

( git push )

Agora o projeto também está online.
🧠 O segredo para nunca esquecer
Grava esta sequência:

### Criar
   ↓
### Adicionar (git add)
   ↓
### Commit
   ↓
### Push

É o fluxo que vais repetir centenas de vezes ao longo da tua carreira.😊💻

## By: ipboy-cipher
