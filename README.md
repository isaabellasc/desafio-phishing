# Desafio-Phishing: Criação de um Phishing com o Kali Linux

O desafio proposto consiste em capturar senhas de rede sociais utilizando o Kali Linux.

1. Iniciei a VM do Kali Linux, acessei o PowerShell. É necessario estar com acesso root, então digitei o comando `sudo su` e colocei a senha de acesso da máquina.
2. Para o projeto é utilizada a ferramenta Setoolkit. Para iniciá-la digitei o comando `setoolkit`.
3. Dentro do setoolkit selecionei a `opção 1 - Social-Engineering Attacks` do menu:

   ![Captura de tela 2024-01-12 194500](https://github.com/isaabellasc/desafio-phishing/assets/149950274/8be531d2-2254-4b32-a928-54ae322f28ce)

4. No próximo menu selecionei a `opção 2 - Web Site Attack Vectors`:

   ![Captura de tela 2024-01-12 194511](https://github.com/isaabellasc/desafio-phishing/assets/149950274/a2c19abb-a0e4-438b-b806-fd3407ea7fac)

5. Escolhi a `opção 3 - Credential Harvester Attack Method`:

   ![Captura de tela 2024-01-12 194520](https://github.com/isaabellasc/desafio-phishing/assets/149950274/6514c39f-e573-425b-b729-645141a625dc)

6. Neste ponto o desafio solicita que seja selecionada a `opção 2 - Site Cloner`, porém eu não estava conseguindo realizar a captura do login e da senha, mesmo tentando com outros sites além do facebook, então, seguindo a dica que alguns colegas deram no Fórum a `opção 1 - Web Templates` foi selecionada:

   ![Captura de tela 2024-01-12 194532](https://github.com/isaabellasc/desafio-phishing/assets/149950274/e765ea29-582d-4a36-9a5d-8706f416a34f)

7. Escolhi o template do Google:

   ![Captura de tela 2024-01-12 203237](https://github.com/isaabellasc/desafio-phishing/assets/149950274/15783a09-fb16-491b-a46d-6d7669a71a30)

8. Acessei por uma aba anônima o ip da máquina, coloquei um e-mail e senha:

   ![Captura de tela 2024-01-12 203312](https://github.com/isaabellasc/desafio-phishing/assets/149950274/f3ff8ba7-b46e-4f7c-9b5a-86142c0c6343)

9. Após dar enter a página redireciona para a página autêntica do Google e no Kali é possível verificar os dados roubados:

    ![Captura de tela 2024-01-12 203325](https://github.com/isaabellasc/desafio-phishing/assets/149950274/65e40b72-b189-4003-8ab4-ded66f330298)
