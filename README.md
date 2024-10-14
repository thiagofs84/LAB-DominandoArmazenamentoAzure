# LAB-DominandoArmazenamentoAzure

## 1️⃣ - CRIAÇÃO DE CONTA DE ARMAZENAMENTO

* Pode receber os seguintes tipos de dados
Conteinere blob
files
filas e tabela

> o Nome tem que ser mundialmente exclusivo. tem que 3 a 24 caracteres. sem letras maiusculas e sem caracteres especiais.
> desempenho: pode ser standard para operações normais cobrado conforme o uso ou premium para operações com baixa latencia, cobrado independente do uso.
>
### - Parametros escolhidos para criação da conta
![link](https://github.com/thiagofs84/LAB-DominandoArmazenamentoAzure/blob/main/Cria%C3%A7%C3%A3o%20de%20Conta.png)

### - Parametros escolhidos para Compartilhamento de Arquivos
![link2](https://github.com/thiagofs84/LAB-DominandoArmazenamentoAzure/blob/main/NovoCompartArquivos.JPG)

### - Conexão



![link3](https://github.com/thiagofs84/LAB-DominandoArmazenamentoAzure/blob/main/ScriptConexao.JPG)

> Dica - Para fazer o acesso a partir de uma máquina, criar uma máquina virtual no Azure e executar nela, através do Power Shel o script apresentado.
A conexão, funciona com porta TCP 445 (porta SMB)


## 2️⃣ - MIGRAÇÃO

### BANCO DE DADOS

![link3](https://github.com/thiagofs84/LAB-DominandoArmazenamentoAzure/blob/main/ProjetoMigracaoBD.JPG)

![link4](https://github.com/thiagofs84/LAB-DominandoArmazenamentoAzure/blob/main/TokenAcessoCompart.JPG)

'https://thiagofs84.blob.core.windows.net/novoteste?sp=racwdlmeop&st=2024-10-14T16:50:54Z&se=2024-10-15T00:50:54Z&spr=https&sv=2022-11-02&sr=c&sig=iY7NUf4f0mCisMO1ye%2B9xbOLoafSVgmSiOymlKMnVRI%3D


