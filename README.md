# 🚀 Servidores Linux na Prática

Este repositório acompanha o curso publicado no YouTube com foco nos fundamentas de Linux simulando uma infraestrutura real, utilizando virtualbox como ambiente de virtualização. Aqui você encontrará materiais de apoio, comandos comentados, exercícios e documentação para cada etapa do projeto.

---

## 🎓 Proposta Pedagógica

**Objetivo Geral:**  
Capacitar alunos e entusiastas de tecnologia a instalar, configurar e administrar um servidor Linux completo, com aplicações reais como GLPI e sistemas de documentação técnica, seguindo boas práticas de segurança e gestão.

---

## 📚 Estrutura das Aulas

Cada módulo possui conteúdo explicativo e um exercício prático para reforçar o aprendizado.

---

### 1. 🧱 Preparação do Ambiente

- Introdução ao virtualbox e virtualização
- Verificação de recursos do host (CPU, RAM, disco)
- Download da ISO oficial do Ubuntu Server LTS
- Criação e configuração da VM com recursos mínimos
- Montagem da ISO e início da instalação

🎯 *Objetivo: preparar o terreno para a instalação do servidor.*

**🧪 Exercício 01:**
1. Instale o virtualbox em seu computador ou notebook.
2. Crie uma VM com 1 vCPU, 4GB RAM e 30GB de disco.
3. Monte a ISO do Ubuntu Server LTS e inicie a instalação.
4. Poste um print da tela de instalação no LinkedIn com a hashtag `#ServidorLinuxNaPrática`.

---

### 2. 🖥️ Configuração do Ubuntu Server

- Snapshot e Atualização de pacotes do sistema
- Instalar e configurar o Servidor SSH
- Configuração de rede (IP fixo ou DHCP reservado)
- Instalação de ferramentas básicas para administração

🎯 *Objetivo: garantir um sistema operacional funcional e acessível remotamente.*

**🧪 Exercício 02:**
1. Instale o Ubuntu Server com SSH habilitado.
2. Configure IP fixo ou DHCP reservado.
3. Instale `curl`, `wget`, `net-tools`, `vim`.
4. Poste no Linkedin a configuração da rede e o acesso remoto via ssh e marque meu nome!

---

### 3. 🌐 Configuração do Servidor Web

- Instalação do Apache, PHP e extensões
- Instalação do MariaDB/MySQL 
- Instalação e configuração do phpMyAdmin
- Correção do método de acesso ao PHPMyadmin
- Teste do ambiente com página PHP

🎯 *Objetivo: montar a base para aplicações web dinâmicas.*

**🧪 Exercício 03:**
1. Instale Apache, PHP e MariaDB.
2. Crie uma página PHP com `phpinfo()`.
3. Poste um print da página com o apache funcionando no LinkedIn com a hashtag `#ServidoresLinuxNaPrática` e marque meu nome.

---

### 4. 🧩 Instalação de Aplicações Reais

- Criação e configuração de banco de dados via cli
- Criação e configuração de banco de dados via phpmyadmin
- Instalação do GLPI (gestão de ativos e chamados)
- Configuração de backups automáticos

🎯 *Objetivo: aplicar o conhecimento em soluções reais de mercado.*

**🧪 Exercício 04:**
1. Crie o banco de dados
2. Adicione um usuário ao banco de dados e atribua as permissões de acesso e uso do banco
3. Instale o GLPI.
4. Poste no LinkedIn a página do phpmyadmin funcionando, marque meu nome e use a hashtag `#ServidoresLinuxNaPrática`.

---

### 5. 🔐 Segurança e Acesso

- Configuração de firewall (ufw ou iptables)
- Criação de usuários com permissões específicas
- Acesso remoto seguro (SSH com chave, fail2ban)
- Criação de snapshot da VM

🎯 *Objetivo: proteger o servidor e garantir acesso seguro.*

**🧪 Exercício 05:**
1. Configure o `ufw` para permitir apenas portas essenciais.
2. Crie um usuário com acesso restrito.
3. Configure acesso SSH com chave pública.
4. Poste no LinkedIn um print do seu `ufw status`, marque o meu nome e use a hashtag `#ServidoresLinuxNaPrática`..

---

### 6. 📑 Documentação e Finalização

- Registro de configurações e credenciais
- Documentação de IP, hostname e serviços ativos
- Validação de acesso externo às aplicações
- Organização e controle de tarefas no Monday

🎯 *Objetivo: consolidar o projeto com documentação e controle.*

**🧪 Exercício 06:**
1. Crie um documento com IP, hostname e serviços ativos.
2. Teste o acesso externo às aplicações.
3. Poste no LinkedIn uma dica de documentação que você usou.

---

## 🧪 Exercício Extra – Simulação de Recuperação de Desastre

🎯 *Objetivo: demonstrar o poder da virtualização na recuperação rápida de falhas críticas.*

1. Crie uma VM com Apache e uma página personalizada.
2. Exporte a VM como `.ova` ou crie um snapshot.
3. Delete o disco virtual ou corrompa o Apache.
4. Restaure a VM e valide o retorno da página.
5. Poste no LinkedIn um print da página restaurada com a hashtag `#ServidoresLinuxNaPrática`.

---

## 📦 Material de Apoio

Todos os comandos, checklists e arquivos complementares estão disponíveis no Google Drive:

🔗 [Acesse aqui o material de apoio](https://drive.google.com/drive/folders/1txh9CA1mzWBLe63BD-NWRQ0SAUzgUVx-?usp=sharing)

> Os arquivos estão organizados por módulo, com comandos comentados e passo a passo para acompanhar cada vídeo.

---

## 🎥 Metodologia no YouTube

- Aulas práticas e passo a passo
- Explicações acessíveis e exclusivo para iniciantes
- Material complementar e comandos comentados
- Espaço para dúvidas e interação nos comentários

🔗 [Acesse aqui as videoaulas no youtube](https://www.youtube.com/playlist?list=PLX-2Ss2Z7fNiMcUyf-Yk9MB3byCBI6dvf)

> As videoaulas estão organizadas por temas com explicações didáticas e exemplos práticos para uma melhor compreensão do tema.

---

## 🏁 Resultado Esperado

Ao final do curso, o aluno terá um servidor Linux funcional, seguro e com aplicações reais instaladas, pronto para uso educacional ou pessoal.

Os conhecimentos aqui adquiridos podem ser aplicados em ambientes corporativos e usados em ferramentas profissionais como vmware, proxmox, hyper-v e outros.

---

**Siga o projeto no LinkedIn e marque seus avanços com a hashtag `#ServidoresLinuxNaPrática`!**

## 👤 Conecte-se comigo

Se você está acompanhando este projeto, aplicando os exercícios ou quer compartilhar seu progresso, me marque no LinkedIn!  
Estou sempre aberto a trocar ideias, tirar dúvidas e acompanhar a evolução dos alunos.

🔗 **Meu perfil profissional:** [Daniel no LinkedIn](https://www.linkedin.com/in/daniel-santos-it/)
