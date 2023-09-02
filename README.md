# Resumo GIT e GitHub

Repositório para armazenar resumos sobre Git e GitHub.

# 📃Documentação 

• [Documentação Git](https://git-scm.com/doc)

• [Documentação GitHub](https://docs.github.com/pt)

# 💻Resumo

Versionamento de código são Softwares que controlam as versões de um arquivo ao longo do tempo, registrando o histórico de atualizações, gerenciando quais foram as alterações, a data, autor e etc.

Tipos de sistemas de controle de versão: 

 1. VCS centralizado (CVCS):

        Segue a topologia em estrela, havendo apenas um único repositório central, mas várias cópias de trabalho, uma para cada desenvolvedor. A comunicação entre uma área de trabalho e outra passa obrigatoriamente pelo repositório central. Teremos as areas de trabalho conectados a um unico servidor. A única desvantagem é que se ficar fora do ar, se houver perca de dados, acaba não conseguindo não salvar. Ex.: CVS, Subversion

2. VCS distribuído (DVCS):

       O banco de versão é duplicado localmente, clona o repositório completo, o que inclui o histórico de versões, cada clone é como um backup, possibilita um fluxo de trabalho flexível, possibilidade de trabalhar sem conexão á rede; Ex.: Git e mercurial

O que é o GIT? 

    + É um sistema de controle de versão distribuído, 
    + Gratuito e Open Source (código aberto),
    + Ramificações (branching) e fusões (merging) eficientes, 
    + Leve e rápido.

Breve histórico do GIT:

       2002 - O projeto do núcleo (Kernel) do linux, que é open source, começa a utilizar o BitKeeper, que é um sistema de controle de versão proprietário (DVCS proprietário). 

       2005 - Após conflitos com a comunidade, o BitKeeper rescinde a licença gratuita. O que leva a Linux Torvalds, o criador do Linux, e sua equipe a desenvolverem sua propria ferramenta, o GIT.

Configurando o GIT e seus comandos:

1. Configuração inicial:

       git config --global user.name "Seu Nome"
       git config --global user.email "seuemail@example.com"

2. Comandos básicos:

       git init: Transforma um diretório em um repositório GIT. 
       git clone<URL>: Faz uma cópia local de um repositório remoto.
       git add<file>: Adiciona suas alterações ao índice. 
       git commit -m"mensagem": Registra alterações que foram adicionadas pelo comando git add no repositório.
       git status: Saiba quais arquivos estão modificados e quais estão prontos para o commit. 
       git pull: Puxa as alterações do repositório remoto para o local.
       git push: Envia as alterações do repositório local para o remoto.
       git branch: Ver todas as ramificações atuais do projeto. 
       git checkout<branch>: Mudar para uma branch específica para trabalhar nela.
       git --version: Mostra a versão do GIT.
       git merge<other branch>: Unir as mudanças de uma branch a outra. 
    
GitHub é a plataforma de hospedagem de código para controle de versão com GIT, e colaboração. 

Histórico do GitHub:

      2008 - Desenvolvido por Chris Wanstrath, J. Hyett, Tom Preston-Werner e Scott Chacon

      2018 - Vitima de um dos maiores ataques de DDoS (ataque distribuido de negação de serviço) ocasionando uma sobrecarga do sistema, comprado pela Microsoft por 7,5 bilhões. 

Iniciando um projeto GIT

     Abrir uma nova pasta no pc e colocar o nome do projeto;
     Entrar na pasta criada, clicar no botão direito e abrir no Vscode;
     Utilizar o comando readme.md; 
     Abrir o terminal do GIT e colocar o comando git init;
     git add readme.md manda os arquivos para a área do stading;
     
Atualizando projetos no GITHUB

    No VsCode abrir o terminal do Git bash here;
    git status (verificar se tem arquivo novo ou atualizado);
    git add . (adicionado os arquivos novos ou atualizados);
    git commit -a -m “ ”;
    git pull (puxa as alterações feitas no nosso repositório remoto para pc, usa-se apenas se você fez alterações no repositório remoto, ou se forem projetos trabalhados paralelamente com outras pessoas);
    git push origin main (envia para o GitHub);

Clonando projetos do GITHUB

    Acessar o GitHub e procurar o projeto que deseja clonar;
    Copiar a URL do repositório;
    Criar uma pasta no pc com o nome do projeto;
    Acessar o CMD;
    No CMD Digitar cd + nomeDoProjeto;
    Digitar  git clone + nomeDoProjeto que eu criei;
    Abrir a pasta no VsCode e digitar git init;

Outra forma de clonar projetos do GITHUB

    Após clonar a URL do projeto do GitHub e criar a pasta no PC;
    Acesso a pasta criada e abro o Git Bash here;
    Digitar git clone + URL copiada;

Adicionando projetos no GITHUB

    git init
    git add . 
    git commit -m “”
    Acessar o GitHub, criar um repositório com o nome do projeto;
    copiar os comandos do segundo quadro e colar no terminal do VsCode;

# 🔍Referências

[https://github.blog/]

