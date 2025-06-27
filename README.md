# ☁️ Estudo sobre Máquinas Virtuais no Microsoft Azure

Este repositório foi criado como parte do desafio da DIO sobre o gerenciamento de máquinas virtuais no Azure. Apesar de não ter executado todas as etapas na prática, organizei aqui os principais conceitos que estudei nas aulas e nas documentações, com o objetivo de reforçar o aprendizado e manter um material de apoio para quando for aplicar isso em projetos futuros.

---

# O que aprendi até aqui

# Introdução ao Azure
- O Azure é a plataforma de computação em nuvem da Microsoft.
- Permite criar e gerenciar diversos recursos, como máquinas virtuais, bancos de dados, redes virtuais, entre outros.

# Conceitos sobre Máquinas Virtuais (VMs)
- Uma VM é um ambiente virtualizado que simula um computador físico.
- No Azure, é possível criar VMs com sistemas operacionais Windows ou Linux.
- Durante a criação da VM, é necessário configurar:
  - **Grupo de recursos**
  - **Imagem do sistema operacional**
  - **Tamanho da máquina**
  - **Tipo de autenticação (senha ou chave SSH)**
  - **Regras de rede (como liberar a porta 22 para SSH)**

# Acesso remoto
- O acesso geralmente é feito via SSH (para Linux) ou RDP (para Windows).
- É necessário liberar as portas corretas e configurar as credenciais no momento da criação.

# Dicas importantes
- **Economia:** Desligar as VMs quando não estiverem em uso ajuda a economizar créditos.
- **Segurança:** Usar autenticação por chave SSH é mais seguro que senha.
- **Organização:** Usar nomes claros para grupos de recursos e VMs facilita o gerenciamento.

---

# Fontes utilizadas

- Aulas da plataforma DIO
- [Documentação Oficial do Azure - Máquinas Virtuais](https://learn.microsoft.com/pt-br/azure/virtual-machines/)
- Tutoriais no canal Microsoft Learn

---

# Considerações finais

Embora eu ainda não tenha colocado em prática a criação de uma VM, esse estudo me deu uma base sólida para começar a usar o Azure com mais confiança. Este repositório serve como referência rápida para os principais pontos e vai ser útil quando eu for aplicar isso na prática.

---

**Autor:** Vinicius Matos  
**Desafio:** Gerenciamento de Máquinas Virtuais no Azure – DIO
