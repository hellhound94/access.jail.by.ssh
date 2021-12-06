# access.jail.by.ssh
Acesse um jail do FreeBSD por SSH

# Cenário
Você possui um Servidor TrueNAS rodando.
Neste servidor existe Jail também, e você quer acessar ele direto da sua máquina.

# Instruções
Abra um cliente SSH
Configure o básico, IP do Servidor, Porta, Usuário e Senha e conecte.

Quando o cliente lhe fornecer o terminal do servidor entre com:

sudo iocage console JailName

