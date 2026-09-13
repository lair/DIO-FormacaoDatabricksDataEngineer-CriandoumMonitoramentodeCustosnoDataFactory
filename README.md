# DIO

## Formação Databricks Data Engineer

### Criando um Monitoramento de Custos no Data Factory

Resumo de Atividade do Curso Formação Databricks Data Engineer da DIO

# Introdução ao Microsoft Azure para Estudantes

Este curso apresenta uma introdução visual e prática ao Microsoft Azure, utilizando uma conta Microsoft de estudante. O objetivo é mostrar os primeiros passos no portal, a criação e organização de recursos e as principais opções de configuração, monitoramento e automação.



---

## Objetivos do curso

Ao final da aula, o aluno deverá compreender como:

- Acessar o portal do Azure com uma conta de estudante.
- Localizar serviços e recursos utilizando a busca.
- Personalizar a página inicial do portal.
- Adicionar e remover recursos dos favoritos.
- Criar e organizar dashboards.
- Selecionar a assinatura correta.
- Criar grupos de recursos.
- Criar um recurso no Azure.
- Configurar nome, região e opções de rede.
- Utilizar tags para organizar recursos e controlar custos.
- Revisar e validar uma implantação.
- Acompanhar a criação de recursos pelas notificações.
- Configurar permissões e bloqueios de segurança.
- Monitorar recursos por meio de métricas e logs.
- Utilizar o Cloud Shell.
- Baixar e reutilizar templates de infraestrutura.
- Utilizar a documentação e recursos de assistência do Azure.

---

## 1. Acesso ao portal do Azure

O curso utiliza uma conta Microsoft de estudante para acessar o ambiente do Azure.

A conta utilizada influencia:

- As assinaturas disponíveis.
- Os recursos que podem ser criados.
- As permissões do usuário.
- Os créditos disponíveis.
- As regiões e serviços acessíveis.

Antes de criar qualquer recurso, é importante confirmar se a assinatura correta está selecionada, principalmente quando se utiliza uma conta gratuita ou educacional.

---

## 2. Busca por recursos e serviços

A tela inicial do Azure disponibiliza uma ferramenta de busca para localizar rapidamente:

- Serviços.
- Recursos.
- Configurações.
- Grupos de recursos.
- Dashboards.
- Opções de gerenciamento.

A busca é uma das principais formas de encontrar funcionalidades dentro do portal.

Determinados recursos somente poderão ser criados se a conta possuir:

- Uma assinatura ativa.
- Créditos disponíveis.
- Permissões suficientes.
- Compatibilidade com o tipo de recurso escolhido.

Caso a conta não tenha autorização ou suporte para determinado serviço, o Azure poderá impedir sua criação.

---

## 3. Favoritos e acesso rápido

O portal permite adicionar serviços aos favoritos.

Os favoritos servem como atalhos para os recursos mais utilizados e ajudam a tornar o acesso mais rápido e organizado.

### Possíveis ações

- Adicionar um serviço aos favoritos.
- Remover um serviço dos favoritos.
- Consultar os serviços favoritos na página inicial.
- Organizar o portal conforme as necessidades do projeto.

Essa personalização é útil quando o usuário trabalha frequentemente com os mesmos serviços.

---

## 4. Dashboards

O dashboard funciona como um painel personalizado para acompanhar recursos e informações importantes.

É possível:

- Criar um ou mais dashboards.
- Editar dashboards existentes.
- Adicionar componentes e informações.
- Remover componentes.
- Fixar métricas, gráficos e recursos.
- Criar dashboards separados por projeto ou finalidade.

### Exemplos de organização

- Dashboard de um projeto específico.
- Dashboard de um curso.
- Dashboard para acompanhamento de pipelines.
- Dashboard com métricas de desempenho.
- Dashboard para monitoramento de custos.

A criação de vários dashboards permite separar visualmente informações de diferentes ambientes e projetos.

---

## 5. Assinaturas do Azure

A assinatura define o ambiente financeiro e administrativo no qual os recursos serão criados.

Ao iniciar uma implantação, é necessário selecionar a assinatura correta.

A assinatura está relacionada a:

- Permissões.
- Recursos disponíveis.
- Cobrança e custos.
- Créditos educacionais.
- Limites de utilização.
- Organização dos recursos.

Em uma conta de estudante, é importante acompanhar o consumo dos créditos disponíveis. Durante a aula, foi mencionada a existência de créditos educacionais, possivelmente no valor de **US$ 100**, destinados à criação e aos testes de recursos.

> O valor e as condições dos créditos devem ser confirmados diretamente na conta do Azure, pois podem variar conforme a oferta vigente.

---

## 6. Grupos de recursos

Um grupo de recursos é uma estrutura lógica utilizada para organizar recursos relacionados a um mesmo projeto.

Por exemplo, um projeto pode utilizar:

- Máquinas virtuais.
- Bancos de dados.
- Redes virtuais.
- Serviços de armazenamento.
- Pipelines.
- Aplicações.
- Serviços de monitoramento.

Esses elementos podem ser reunidos em um único grupo de recursos.

### Benefícios

Os grupos de recursos facilitam:

- A organização do ambiente.
- O gerenciamento dos recursos.
- A aplicação de permissões.
- A atualização dos componentes.
- O controle de custos.
- O monitoramento do projeto.
- A exclusão organizada dos recursos.

Todo recurso criado no Azure normalmente precisa estar associado a um grupo de recursos novo ou existente.

### Boas práticas

- Criar grupos separados por projeto.
- Utilizar nomes padronizados.
- Evitar misturar recursos de projetos diferentes.
- Usar tags para complementar a organização.
- Considerar o ciclo de vida dos recursos antes de agrupá-los.

---

## 7. Criação de um recurso

O processo geral de criação de um recurso envolve as seguintes etapas:

1. Acessar a opção de criação de recursos.
2. Pesquisar o serviço desejado.
3. Selecionar a assinatura.
4. Criar ou selecionar um grupo de recursos.
5. Informar o nome do recurso.
6. Escolher a região.
7. Configurar rede, segurança e demais opções.
8. Adicionar tags.
9. Revisar as configurações.
10. Executar a validação.
11. Confirmar a implantação.
12. Acompanhar o progresso pelas notificações.

Cada serviço possui suas próprias opções e requisitos. Alguns recursos apresentam configurações mais simples, enquanto outros exigem conhecimentos avançados de rede, segurança, armazenamento ou computação.

---

## 8. Nomeação dos recursos

Os recursos devem receber nomes válidos conforme as regras do serviço utilizado.

Dependendo do recurso, podem existir restrições relacionadas a:

- Caracteres permitidos.
- Tamanho do nome.
- Uso de espaços.
- Letras maiúsculas e minúsculas.
- Nomes duplicados.
- Disponibilidade global do nome.

Uma convenção de nomes ajuda a identificar rapidamente o recurso e o projeto ao qual ele pertence.

### Exemplo de padrão

```text
<ambiente>-<projeto>-<tipo-de-recurso>-<regiao>
```

Exemplo:

```text
dev-projetoazure-storage-br
```

O padrão exato deve ser adaptado às regras do serviço e às necessidades da organização.

---

## 9. Escolha da região

A região determina a localização física ou geográfica na qual o recurso será implantado.

A escolha deve considerar:

- Proximidade dos usuários.
- Localização do cliente.
- Latência.
- Disponibilidade do serviço.
- Requisitos de conformidade.
- Custo.
- Desempenho.
- Necessidade de redundância.

Nem todos os serviços estão disponíveis em todas as regiões. Também pode haver diferença de preço e disponibilidade entre regiões.

Quando possível, deve-se escolher uma região próxima aos usuários e compatível com os requisitos do projeto.

---

## 10. Configuração de rede

Durante a criação de alguns recursos, é possível escolher como eles serão acessados pela rede.

Entre as possibilidades estão:

- Acesso por rede pública.
- Acesso por rede privada.
- Integração com redes virtuais.
- Uso de endpoints privados.
- Restrição de acesso a determinados clientes ou serviços.

A configuração adequada depende do nível de segurança e do tipo de aplicação.

### Considerações

- Recursos públicos são mais acessíveis, mas exigem cuidados adicionais de segurança.
- Recursos privados podem restringir o acesso à rede interna.
- O cliente pode exigir que os dados e serviços permaneçam em uma rede privada.
- A configuração de rede pode ser aprofundada em cursos mais avançados.

---

## 11. Tags

As tags são pares de chave e valor utilizados para classificar e identificar recursos.

### Exemplos

```text
Projeto = CursoAzure
Ambiente = Desenvolvimento
Equipe = Marketing
CentroDeCusto = CC001
Cliente = ClienteA
Responsavel = EquipeCloud
```

As tags ajudam a:

- Separar recursos por projeto.
- Identificar o responsável.
- Organizar ambientes.
- Classificar recursos por equipe.
- Analisar custos.
- Criar relatórios.
- Facilitar a administração.

A utilização de um padrão de tags é importante para manter o ambiente organizado.

---

## 12. Revisão e validação

Antes da implantação, o Azure apresenta uma etapa de revisão das configurações.

Nessa etapa, o usuário pode conferir itens como:

- Assinatura.
- Grupo de recursos.
- Nome.
- Região.
- Configurações de rede.
- Configurações de segurança.
- Tags.
- Opções específicas do serviço.

O Azure também executa uma validação para verificar se a configuração está correta.

Se houver problemas, a plataforma informa quais itens precisam ser corrigidos antes da criação.

---

## 13. Implantação e notificações

Após a confirmação, o Azure inicia a implantação do recurso.

O andamento pode ser acompanhado por meio da área de notificações.

As notificações podem indicar:

- Início da implantação.
- Recursos sendo criados.
- Operações concluídas.
- Falhas.
- Erros de configuração.
- Implantação concluída com sucesso.

Mesmo quando a criação parece rápida, é importante aguardar a confirmação final antes de utilizar o recurso.

---

## 14. Templates e infraestrutura como código

O Azure permite baixar um template baseado na configuração realizada durante a criação de um recurso.

Esse template pode ser reutilizado para criar outros ambientes de forma padronizada.

### Benefícios

- Automatização.
- Reutilização de configurações.
- Maior velocidade.
- Redução de erros manuais.
- Padronização dos ambientes.
- Facilidade para criar vários recursos semelhantes.
- Possibilidade de versionar os arquivos em um repositório Git.

Um exemplo de uso seria criar várias máquinas virtuais com configurações semelhantes, alterando apenas valores como:

- Nome.
- Região.
- Tamanho.
- Grupo de recursos.
- Identificadores do ambiente.

O conteúdo exato do template depende do serviço utilizado e da tecnologia de implantação adotada no Azure.

---

## 15. Git e DevOps

A aula menciona que a configuração do Git e do DevOps será abordada de maneira mais avançada em cursos posteriores.

Essa integração pode ser utilizada para:

- Armazenar templates.
- Versionar arquivos de infraestrutura.
- Automatizar implantações.
- Criar pipelines.
- Padronizar ambientes.
- Controlar alterações realizadas no projeto.

A configuração detalhada não foi desenvolvida nesta aula introdutória.

---

## 16. Controle de acesso

O Azure permite controlar quais usuários podem acessar ou administrar os recursos.

É possível definir:

- Usuários autorizados.
- Grupos de usuários.
- Funções.
- Escopos de acesso.
- Permissões de leitura.
- Permissões de edição.
- Permissões administrativas.

O acesso pode ser configurado em diferentes níveis, como:

- Recurso.
- Grupo de recursos.
- Assinatura.
- Outros escopos administrativos.

A recomendação geral é conceder somente as permissões necessárias para cada pessoa ou equipe.

---

## 17. Bloqueios de segurança

Os bloqueios protegem recursos contra alterações ou exclusões acidentais.

Entre os tipos de bloqueio mencionados estão:

### Somente leitura

Impede alterações no recurso, permitindo apenas sua consulta.

### Bloqueio contra exclusão

Impede que o recurso seja excluído acidentalmente.

Os bloqueios podem ser aplicados a recursos ou grupos de recursos e são úteis em ambientes importantes ou compartilhados.

Antes de remover um bloqueio, é necessário avaliar os impactos da ação.

---

## 18. Monitoramento

O Azure oferece recursos para acompanhar o comportamento dos serviços implantados.

As ferramentas de monitoramento podem incluir:

- Métricas.
- Logs.
- Gráficos.
- Alertas.
- Histórico de operações.
- Indicadores de desempenho.
- Informações de disponibilidade.

O monitoramento permite identificar problemas e acompanhar o funcionamento dos recursos.

### Exemplo

Um pipeline pode ser acompanhado para verificar:

- Se foi executado.
- Se terminou com sucesso.
- Se apresentou erro.
- Quanto tempo levou.
- Qual foi o resultado da execução.

---

## 19. Fixação de métricas no dashboard

As informações de monitoramento podem ser fixadas no dashboard.

Isso permite visualizar rapidamente:

- Status dos recursos.
- Métricas de desempenho.
- Resultados de pipelines.
- Indicadores de sucesso ou falha.
- Informações importantes do projeto.

A criação de painéis personalizados facilita o acompanhamento diário do ambiente.

---

## 20. Cloud Shell

O Azure Cloud Shell é um ambiente de linha de comando acessível pelo portal.

Ele pode ser utilizado para:

- Executar comandos.
- Administrar recursos.
- Criar serviços.
- Consultar informações.
- Trabalhar com templates.
- Automatizar tarefas.
- Gerenciar a infraestrutura sem sair do portal.

O Cloud Shell é uma alternativa à configuração manual pela interface gráfica e será especialmente útil em atividades mais avançadas.

---

## 21. Documentação e assistência

O portal do Azure oferece acesso a materiais de apoio, como:

- Documentação oficial.
- Guias de criação.
- Tutoriais.
- Vídeos.
- Exemplos de configuração.
- Informações detalhadas dos produtos.

Também foi mencionada uma ferramenta de assistência virtual capaz de orientar o usuário durante a criação de serviços e indicar etapas relacionadas à documentação.

Ao encontrar uma opção desconhecida, é recomendável consultar a documentação correspondente antes de prosseguir.

---

## 22. Boas práticas apresentadas

Com base no conteúdo da aula, algumas boas práticas são:

- Confirmar a assinatura antes de criar recursos.
- Organizar os componentes por grupos de recursos.
- Adotar um padrão de nomenclatura.
- Escolher a região de acordo com o projeto.
- Utilizar tags desde o início.
- Revisar as configurações antes da implantação.
- Acompanhar as notificações da criação.
- Controlar permissões de usuários.
- Aplicar bloqueios em recursos importantes.
- Monitorar métricas e logs.
- Utilizar dashboards personalizados.
- Evitar o desperdício dos créditos de estudante.
- Reutilizar templates para manter a padronização.
- Consultar a documentação oficial.
- Aprender posteriormente automação, Git, DevOps e pipelines.

---

## 23. Fluxo resumido de criação

```text
Acessar o portal
       |
       v
Pesquisar o serviço
       |
       v
Selecionar a assinatura
       |
       v
Criar ou selecionar o grupo de recursos
       |
       v
Definir nome e região
       |
       v
Configurar rede e segurança
       |
       v
Adicionar tags
       |
       v
Revisar configurações
       |
       v
Validar
       |
       v
Implantar
       |
       v
Acompanhar notificações
       |
       v
Monitorar e adicionar informações ao dashboard
```

---

## 24. Conclusão

A aula apresentou os fundamentos para começar a utilizar o Microsoft Azure com uma conta de estudante.

O conteúdo principal envolveu:

- Navegação pelo portal.
- Favoritos.
- Dashboards.
- Assinaturas.
- Grupos de recursos.
- Criação de serviços.
- Regiões.
- Redes.
- Tags.
- Segurança.
- Permissões.
- Bloqueios.
- Validação.
- Implantação.
- Notificações.
- Monitoramento.
- Cloud Shell.
- Templates de automação.

---


