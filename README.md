# **Comandos-Ubuntu**<br>
- **sudo**: concede privilegio de administrador<br>
- **apt**: gerenciador de pacotes<br>
- <img width="183" height="21" alt="image" src="https://github.com/user-attachments/assets/6f8a2f6f-85a7-424f-a83b-a5bf75496a2b" /> atualiza a lista de pacotes disponíveis (só consulta, não instala nada)<br>
- <img width="66" height="21" alt="image" src="https://github.com/user-attachments/assets/45e8d58b-eb7a-4f4e-9d2b-4fad04e3cb2f" /> instala as atualizações disponíveis para os pacotes que você já tem<br>
- <img width="183" height="21" alt="image" src="https://github.com/user-attachments/assets/8cdf8a3a-61c2-44d0-9b3f-16c2a9fa8f44" /> reinicia o computador<br>
- <img width="603" height="21" alt="image" src="https://github.com/user-attachments/assets/13cfec60-6798-49a0-b443-48afe2e84243" /><br>
    - install build-essential: ferramenta para compilar código-fonte<br>
    - dkms: recompilar de aplicações para compatibilidade com kernel de convidado (guest)<br>
- <img width="347" height="21" alt="image" src="https://github.com/user-attachments/assets/a8f88ae8-d486-42e7-8c49-cdd5f14d04d7" /> acessa a pasta onde esta o aplicativo para instalar<br>
- <img width="80" height="21" alt="image" src="https://github.com/user-attachments/assets/5f80816f-b0ab-4d83-be9c-f2e2f91d128e" /> o nome do usuário logado <br>
- <img width="292" height="21" alt="image" src="https://github.com/user-attachments/assets/08525057-aa3b-4efa-b79a-6f8d6d54ae7c" /> executa o arquivo<br>
- <img width="144" height="21" alt="image" src="https://github.com/user-attachments/assets/7d7e45b3-d5ec-4870-8289-d637573a4d04" /> serve para listar os modulos <br> 
# Comandos Linux
 
  - Criação de uma nova pasta na máquina física (Host)
    - Caminho <img width="296" height="26" alt="Captura de tela de 2025-08-11 20-14-00" src="https://github.com/user-attachments/assets/446f8d4a-c1cd-470a-a7ed-dafac8f5a504" />
  - Configuração da VM (Guest)

    - Acesso à guia denominada Pasta Compartilhada
    - Criação de uma referência com o caminho <img width="296" height="26" alt="Captura de tela de 2025-08-11 20-14-00" src="https://github.com/user-attachments/assets/446f8d4a-c1cd-470a-a7ed-dafac8f5a504" /> para acessar esta pasta pela VM
  - Após ligar a VM:
    - Adicionando um novo usuário no grupo vboxsf:<img width="257" height="29" alt="Captura de tela de 2025-08-11 20-16-43" src="https://github.com/user-attachments/assets/c43b92cb-4fa2-41c4-a17f-46a2b0fb7002" />

    - VM Reiniciada: <img width="119" height="29" alt="Captura de tela de 2025-08-11 20-17-31" src="https://github.com/user-attachments/assets/c473557b-771e-4953-bce8-a5c57621b4fa" />

    - Acesso ao diretório na VM que referencia a pasta criada na máquina física: C:\sf-VirtualBox-PastaCompatilhada
    - Foi utilizado um comando para imprimir/gravar uma mensagem em um novo arquivo: <img width="267" height="29" alt="Captura de tela de 2025-08-11 20-27-25" src="https://github.com/user-attachments/assets/7ae04f4c-927b-4042-82cb-f8d7854dbce9" /> | <img width="1057" height="31" alt="Captura de tela de 2025-08-11 20-19-40" src="https://github.com/user-attachments/assets/a5df4406-38dc-4b57-85a5-89cc4d232967" />

    - Testamos na máquina física se o novo arquivo criado estava lá 
    - Criamos na máquina física um segundo arquivo
  - Novamente na VM:
  - Utilizando um comando de Leitura: <img width="72" height="23" alt="Captura de tela de 2025-08-11 20-29-55" src="https://github.com/user-attachments/assets/fa868aed-1024-45dc-9ac3-6dde33f83414" />
  - Utilizamos um aplicativo de editor de texto instalado por padrão no Ubuntu para abrir o arquivo e editá-lo: <img width="49" height="30" alt="Captura de tela de 2025-08-11 20-20-36" src="https://github.com/user-attachments/assets/5cf52c9b-0d28-4cd6-9fb7-e580a184baf5" />
- Baixamos um segundo aplicativo de editor/código: 
# comandos 11/08/2025
sudo groupadd criar grupo
sudo mkdir home/ para criar um novo diretorio
sudo chown :nome_do_grupo nome_da_pasta mudar proprietário
sudo chmod Altera permisão
D diretorio Read Write eXecute| R-XR-X
adicionar um usuário a um grupo no SO
sudo addgroup nome_do_grupo
sudo addgroup $USER nome_do_grupo (Ubuntu/Debian desktop)
 Para adicionar um usuário a vários grupos de uma vez só
sudo usermod -aG nome_do_usuario nome_do_grupo1 nome_do_grupo2
sudo usermod -aG nome_do_grupo1 nome_do_grupo2 $USER

 
