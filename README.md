# WSL-WIN11
Como instalar e configurar o WSL no Windows 11

Documentação: https://docs.microsoft.com/pt-br/windows/wsl/install

# O QUE É WSL?

WSL é uma ferramenta do windows que permite que rodemos o linux dentro dele.

# POR QUE MUDEI PARA O WINDOWS COM WSL?

Por que não estava consingo substituir os programas da adobe por programas que rodam no linux e com isso tinha que ficar reiniciando o pc toda vez que queria usar algum programa.
Alem disso vez em quando tinha um pouquinho de trabalho com o GRUB dos sistemas.

# PASSO 1

Abra o terminal do Windows em modo adm e rode esse código

```
wsl --install
```

### COMANDOS ÚTIEIS

Exibe uma lista de distros Linux disponíveis

```
wsl --list --online
```

Instala uma distro diferente do Ubuntu

```
wsl --install -d <DistroName>
```

Atualiza manualmente o kernel WSL Linux

```
wsl --update
```

Eexibe informações gerais de configuração WSL

```
wsl --status
```

Desinstala uma distro

```
wsl --unregister <distro-name>
```

# PASSO 2 

Habilitar o recurso de Máquina Virtual

```
dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart
```

# PASSO 3

Baixar o pacote de atualização do kernel do Linux

[Pacote de aualização](https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi´)

# PASSO 4 

Reiniciar o computador e depois cadastrar user e senha

