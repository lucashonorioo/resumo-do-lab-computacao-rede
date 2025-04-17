# resumo-do-lab-computacao-rede

Nesta aula de laboratório, foram apresentados diversos recursos de criação e configuração no Microsoft Azure, especialmente voltados para máquinas virtuais (VMs), área de trabalho virtual e aplicativos de funções.
Criação de Máquinas Virtuais
Existem diferentes formas de criar uma VM no Azure:

•	Configurações predefinidas:

É possível criar uma máquina com base em ambientes de desenvolvimento/teste ou produção. O usuário também escolhe o tipo de carga de trabalho (uso geral, otimizado para memória, computação otimizada), o que ajusta automaticamente as configurações de hardware para atender à necessidade.

•	Mais VMs e soluções relacionadas:
Nesse caso, além das configurações pré-definidas, a máquina já vem com aplicações instaladas. Por exemplo, é possível criar uma VM Linux já com o WordPress instalado, acelerando a implementação de projetos.

•	Criação manual de VMs:
Quando o cliente opta por criar a máquina manualmente, ele deve configurar:

o	Grupo de recursos

o	Região e zona de disponibilidade (inclusive podendo escolher entre três zonas)

o	Escalonamento

o	Imagem do sistema operacional

o	Configurações de rede (interface, IP, segurança)

o	Gerenciamento (desligamento automático, backup – padrão ou avançado –, regras de alerta)

o	Avançado (extensões para instalação automática ao iniciar a máquina)

o	Marcações (tags) para facilitar o faturamento

o	Revisão final das configurações e exibição dos custos estimados

Essa abordagem manual oferece controle total, mas exige atenção a cada detalhe para garantir o funcionamento adequado da solução.
Área de Trabalho Virtual (Azure Virtual Desktop)
O Azure Virtual Desktop oferece uma solução ideal para empresas que precisam disponibilizar computadores para funcionários em home office sem enviar hardware físico.
As imagens de desktop podem ser criadas de acordo com as necessidades da empresa.
Há duas opções principais de pool de hosts:

•	Pessoal: o funcionário possui uma máquina dedicada, exclusiva para ele.

•	Em pool: a mesma máquina virtual é compartilhada por múltiplos usuários (por exemplo, até cinco colaboradores podem usar a mesma instância).

Essa flexibilidade reduz custos e facilita a gestão de ambientes remotos.
Aplicativos de Funções (Azure Functions)
Na criação de aplicativos de funções, o Azure permite:

•	Escolher entre implantar um código diretamente ou utilizar uma imagem de contêiner (ex.: Docker)

•	Selecionar a pilha de runtime (linguagem de programação e versão)

•	Definir o sistema operacional

•	Configurar outras opções de integração e gerenciamento

Essa abordagem serverless permite criar aplicações escaláveis com foco apenas no código, sem se preocupar com a infraestrutura.




