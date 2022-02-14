# WSL-WIN11
Como instalar e configurar o WSL no Windows 11

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
