# Custos de Hospedagem e Infraestrutura - Xepa+

A hospedagem do Xepa+ será realizada por meio de uma VPS da Hostinger, utilizando o plano VPS KVM 2, com apoio do Cloudflare para proteção e gerenciamento do tráfego do site. Essa estrutura permitirá manter o front-end, o back-end e o banco de dados da plataforma em um mesmo servidor. O plano Hostinger VPS KVM 2 oferece recursos para hospedar os componentes principais do Xepa+, permitindo maior controle sobre o ambiente de execução.

- **Vantagens:** oferece 8 GB de RAM e 100 GB de armazenamento NVMe, permitindo hospedar o front-end, o back-end e o banco de dados no mesmo servidor. É uma opção que oferece controle sobre o ambiente e recursos para iniciar a operação do Xepa+.
- **Limitações:** exige configuração e manutenção do servidor, incluindo atualizações, segurança, HTTPS e banco de dados. Também é necessário verificar as condições de backup e acompanhar o consumo de recursos conforme a plataforma crescer.

## 1. Detalhamento dos Custos

| Item | Finalidade | Custo |
| :--- | :--- | :--- |
| **Hostinger VPS KVM 2** | Hospedagem do front-end, back-end e banco de dados. | R\$ 108,99/mês |
| **Backup** | Cópias de segurança dos dados, incluídos na hospedagem. | R\$ 0,00 |
| **Armazenamento de imagens** | Armazenamento dos arquivos de imagem no espaço disponível no servidor. | R\$ 0,00 |
| **Cloudflare** | Gerenciamento de DNS, proteção básica e distribuição de tráfego. | R\$ 0,00 |
| **Domínio .com.br** | Endereço personalizado para acesso à plataforma, com validade de um ano. | R\$ 40,00/ano |

## 2. Custo Total de Hospedagem

| Período | Hospedagem | Domínio | Total |
| :--- | :--- | :--- | :--- |
| **Mensal** | R\$ 108,99 | - | **R\$ 108,99** |
| **Anual** | R\$ 1.307,88 | R\$ 40,00 | **R\$ 1.347,88** |

O domínio será comprado por meio do serviço de registro de domínio .com.br, pelo valor de R\$ 40,00 por um ano, com possibilidade de renovação por períodos adicionais, conforme as condições do serviço.

## 3. Uso do Cloudflare

O Cloudflare será utilizado como serviço complementar à hospedagem, aproveitando os recursos disponíveis no plano gratuito. Entre suas principais funções estão:

- Gerenciamento de DNS do domínio.
- Proteção básica contra tráfego malicioso.
- Disponibilização de HTTPS, mediante configuração correta do certificado e da conexão com o servidor.
- Cache de conteúdos estáticos, quando aplicável, ajudando a reduzir solicitações diretas ao servidor.