# 🐋 Meus 10 Comandos Docker Essenciais

Este repositório faz parte de uma atividade prática de documentação de comandos básicos do Docker utilizando o Ubuntu Linux.

---

### 1. Verificar a versão do Docker
Mostra a versão atual instalada do Docker Client e Server.
```bash
docker --version
```

### 2. Executar um container de teste
Baixa uma imagem leve de teste e roda um container para validar a instalação.
```bash
sudo docker run hello-world
```

### 3. Listar containers ativos
Exibe todos os containers que estão em execução no momento.
```bash
sudo docker ps
```

### 4. Listar todos os containers
Exibe todos os containers criados na máquina, estejam eles ativos ou parados.
```bash
sudo docker ps -a
```

### 5. Listar imagens baixadas
Mostra todas as imagens de containers armazenadas localmente no computador.
```bash
sudo docker images
```

### 6. Baixar uma imagem sem executar
Faz o download da imagem oficial do servidor web Nginx diretamente do Docker Hub.
```bash
sudo docker pull nginx
```

### 7. Parar um container em execução
Envia um sinal para interromper o funcionamento de um container ativo (substitua pelo ID ou Nome).
```bash
sudo docker stop <id_do_container>
```

### 8. Iniciar um container parado
Lança novamente um container existente que foi interrompido.
```bash
sudo docker start <id_do_container>
```

### 9. Remover um container do sistema
Apaga permanentemente o container do disco (o container precisa estar parado).
```bash
sudo docker rm <id_do_container>
```

### 10. Remover uma imagem local
Exclui a imagem do Nginx armazenada na máquina para liberar espaço.
```bash
sudo docker rmi nginx
```
