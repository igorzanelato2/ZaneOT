# ZaneOT

![Logótipo ZaneOT](ZaneOT-logo.png)

**Gestão de aplicações, processos, inicialização, drivers, análises e otimização para Windows.**

O ZaneOT reúne ferramentas de manutenção numa aplicação gráfica, com pesquisa, pré-visualização das ações e confirmação antes das operações que alteram o sistema.

## Funcionalidades

### Aplicações e processos
- Lista aplicações de ambiente de trabalho e aplicações da Microsoft Store.
- Pesquisa, ordenação e consulta de detalhes das aplicações instaladas.
- Mostra processos em segundo plano com PID, memória e caminho, quando disponíveis.
- Permite terminar um processo ou abrir a desinstalação da aplicação associada, quando o Windows disponibiliza essa ligação.

### Inicialização do Windows
- Consulta aplicações, tarefas agendadas, entradas de registo e serviços de arranque suportados.
- Permite ativar ou desativar itens compatíveis e reverter as alterações suportadas.
- Alguns itens protegidos pelo Windows ou por políticas do dispositivo não podem ser alterados.

### Drivers
- Pesquisa atualizações de drivers oferecidas pelo Windows Update.
- Apresenta fornecedor, dispositivo, versão e data quando disponíveis.
- Permite descarregar e instalar atualizações selecionadas, depois de apresentar os termos aplicáveis.
- A disponibilidade depende do hardware, do Windows Update e das políticas do computador; o ZaneOT não substitui o suporte do fabricante.

### Análise e relatórios
- Executa o scanner integrado para recolher dados sobre processos, arranque, serviços, rede, contas, programas, extensões do navegador e ficheiros em localizações selecionadas.
- O scanner gera um relatório para revisão e não apaga nem modifica os itens analisados.
- Permite abrir o relatório numa janela separada.

### Otimização
- Catálogo pesquisável por ação e grupo, com pré-visualização do conteúdo e indicação de impacto estimado.
- Executa uma ação de cada vez, após confirmação.
- Exige criar um ponto de restauro na sessão antes de iniciar ações modificadoras do pack.
- Inclui diagnósticos somente de leitura para discos e volumes e para energia e bateria; os relatórios são guardados no Ambiente de Trabalho.

## Requisitos
- Windows 10 ou Windows 11, 64 bits.
- Ligação à Internet para pesquisar e descarregar drivers pelo Windows Update.
- Algumas operações do Windows exigem permissões de administrador; o ZaneOT solicita elevação quando necessário.
- O instalador inclui o runtime necessário; não é preciso instalar o .NET à parte.

## Instalar
1. Abra [Releases](https://github.com/igorzanelato2/ZaneOT/releases).
2. Descarregue `ZaneOT-Setup.exe`.
3. Execute o assistente, escolha a pasta e conclua a instalação.
4. Inicie o ZaneOT pelo atalho criado no Ambiente de Trabalho ou no menu Iniciar.

Para remover, use **Desinstalar ZaneOT** no menu Iniciar ou a entrada em Aplicações instaladas do Windows. Os relatórios e definições pessoais são mantidos.

## Utilização responsável
- Reveja o conteúdo e o impacto estimado de cada ação antes de a executar.
- Alterações a serviços, registo, energia ou componentes do Windows podem afetar funcionalidades; mantenha cópias de segurança importantes.
- Crie um ponto de restauro antes de aplicar ações modificadoras.
- Um indicador do scanner é um elemento para revisão, não uma confirmação automática de malware.
- Reveja os termos do Windows antes de instalar drivers.

## Privacidade
Os diagnósticos e relatórios são gerados localmente. A pesquisa, transferência e instalação de drivers utilizam o Windows Update. Esta descrição não substitui uma auditoria independente de privacidade de cada componente.

## Distribuição
Este repositório publica a documentação e o instalador binário para Windows x64; o código-fonte não está incluído nesta versão. A disponibilização do instalador não concede, por si só, uma licença para reutilização ou redistribuição do software.

Consulte as [notas da versão](https://github.com/igorzanelato2/ZaneOT/releases/latest) para o SHA-256 do instalador e os detalhes da versão publicada.
