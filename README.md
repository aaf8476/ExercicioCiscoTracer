# ExercícioCiscoTracer

Instruções do projeto
Para o show da banda de Miguel, será necessário configurar uma rede de computadores. A comunicação entre os membros da equipe de produção, que estarão espalhados pelo teatro, é fundamental para manter todos informados e verificar se nada está fugindo do controle. O agente da banda decidiu modernizar a infraestrutura do show para melhorar essa comunicação. Para ajudá-los, você deve usar o Cisco Packet Tracer para criar uma topologia de rede estrela que permita a toda a equipe se comunicar facilmente.

Passos:
1. Definir o cenário
- Imagine que cada membro da equipe possui um computador que precisa de uma conexão de rede para se comunicar com os outros membros da produção.

2. Montar a topologia
- Crie uma nova topologia no Cisco Packet Tracer; 
- Arraste um switch para o centro da área de trabalho; 
- Arraste quatro PCs e posicione-os ao redor do switch, representando cada membro da equipe de produção.

3. Conectar os dispositivos
- Conecte cada PC a uma porta diferente no switch usando cabos ethernet;
- Visualize os computadores da equipe de produção formando uma estrela ao redor do switch central.

4. Configurar os endereços IP
- Crie um senso de identidade para cada computador, atribuindo nomes e números de endereços IP;
- Configure os endereços IP para as interfaces dos PCs e do switch de acordo com a mesma sub-rede.

5. Testar a comunicação
- Para verificar se todos os computadores estão devidamente configurados, acesse um dos PCs da equipe, abra o prompt de comando e tente fazer um ping para o endereço IP do computador de outro membro da equipe.

Por fim, envie o arquivo do Cisco gerado, junto com um print da tela com a topologia e do comando ping executado para os outros três computadores.

Trabalhe esse código em seu IDE, suba ele para sua conta no GitHub e compartilhe o link desse projeto no campo ao lado para que outros desenvolvedores possam analisá-lo.

# Resolução

## 1. Definição do Cenário

Cada membro da equipe de produção terá um computador que precisa se comunicar com os outros membros.


## 2. Definição da Topologia

Foi criada uma nova topologia no Cisco Packet Tracer, conforme os passos a seguir:

No o Cisco Packet Tracer.
Foi criado um novo projeto.
Arrastando-se um switch para o centro da área de trabalho:

Na barra de dispositivos, foi selecionado um switch e
Arrastado para o centro da área de trabalho.
Da mesma forma foram arrastados quatro PCs e posicionados ao redor do switch:


# Topologia

![image](https://github.com/user-attachments/assets/58b65e2e-8700-430d-8aab-fbe7e98c38c4)

## 3. Conexão dos Dispositivos

Cada PC foi conectado a uma porta diferente no switch usando cabos ethernet:

## 4. Configurar os Endereços IP

Clicando-se em cada PC, depois em Desktop e selecionando-se IP Configuration:

Foram atribuídos os seguintes endereços IP:

PC1:
IP: 192.168.1.2
Máscara de Sub-rede: 255.255.255.0
Gateway Padrão: 192.168.1.1

PC2:
IP: 192.168.1.3
Máscara de Sub-rede: 255.255.255.0
Gateway Padrão: 192.168.1.1

PC3:
IP: 192.168.1.4
Máscara de Sub-rede: 255.255.255.0
Gateway Padrão: 192.168.1.1

PC4:
IP: 192.168.1.5
Máscara de Sub-rede: 255.255.255.0
Gateway Padrão: 192.168.1.1

## 5. Teste de Comunicação

Verificação da conectividade:

Por exemplo, no PC1, dentro do Command Prompt foi digitado o ping 192.168.1.3 para testar a conexão com o PC2.
E assim por diante.

# Telas dos ping - testando a conexão



![image](https://github.com/user-attachments/assets/485c4336-8c11-4b87-8e36-89afe9d9d49f)



![image](https://github.com/user-attachments/assets/7abf6c49-fcb4-4940-ad66-932b9d14cf4f)



![image](https://github.com/user-attachments/assets/b632e87b-5df3-463c-8e75-b576f89c7ea3)


ps. texto elaborado com auxílio do Copilot

![image](https://github.com/user-attachments/assets/784522f8-05ea-49fb-9afb-674c10ce0e67)

