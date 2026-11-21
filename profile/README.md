# LogicDump

**Uma plataforma desktop para rodar aplicativos de IA no seu computador, com os seus dados e os seus modelos.**

O LogicDump hospeda aplicativos especializados, cada um com interface, regras de negócio e dados próprios, e entrega o que eles têm em comum: modelos de IA locais e remotos, servidores MCP, skills, anexos, voz e controle de permissões. Roda em hardware comum e foi pensado para funcionar offline sempre que der.

O host não carrega regra de domínio. Direito, projeto de edificações, simulação e vendas vivem em aplicativos independentes, que usam o mesmo SDK público e podem ser instalados ou removidos sem mexer no núcleo.

## Aplicativos

| Aplicativo | O que faz |
|---|---|
| **Themis** | Apoio ao trabalho jurídico: organiza processos, pesquisa jurisprudência e ajuda a redigir, sempre com a fonte rastreável até o documento de origem. |
| **Daedalus** | Concepção de projetos residenciais sobre o modelo da edificação (IFC) e topografia de precisão. |
| **FlowLine** | Simulação de processos de negócio por eventos discretos, com cenários e análise de resultados. |
| **Mensagens** | WhatsApp e Telegram em uma única interface, com histórico guardado localmente. |
| **AppStudio** | Cria, testa e publica novos aplicativos do LogicDump conversando com a IA. |
| **Office** | Catálogo e controle, pela IA, dos aplicativos ArtCraft instalados. |
| **SkillOptimizer** | Otimiza skills e prompts com GEPA, usando os modelos habilitados no LogicDump. |
| **TrainModel** | Treinamento local de modelos (LoRA/QLoRA) e exportação em GGUF para o LogicDump. |
| **Vendas_IA** | ERP de varejo com PDV e ações por IA, em desenvolvimento. |

## Como construímos

- **Local-first.** Dados e modelos ficam com o usuário; a nuvem é opção, não dependência.
- **Rastreável.** Fonte, resultado intermediário e modo de falha precisam ficar visíveis. O que a IA produz nunca se confunde com o original.
- **Determinístico quando dá, IA quando ajuda.** Parser, regra e banco resolvem muito problema; o modelo entra onde há interpretação ou ambiguidade de verdade.
- **Hardware comum.** Funcionar em CPU e iGPU, com uso responsável de memória, é requisito, não bônus.
- **O domínio manda.** A tecnologia serve ao problema, não o contrário.

## Estado

Em desenvolvimento ativo, para Windows. Os repositórios estão privados por enquanto.

## Sobre o nome

Um *logic dump* é onde o raciocínio, os experimentos e o código deixam de ficar implícitos. Parte vira infraestrutura, parte vira produto, parte vira uma pergunta melhor.
