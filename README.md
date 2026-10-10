# Hoplita Engine 🛠️

Este repositório é dedicado à demonstração e documentação do projeto **Hoplita Engine**, focado em engenharia reversa avançada utilizando **C++** e interface gráfica desenvolvida em **Dear ImGui**.

## 📺 Demonstração em Vídeo
[

![Hoplita Engine - C++ & Dear ImGui](https://img.youtube.com/vi/deAhUpd8Wpg/hqdefault.jpg)

](https://youtu.be/deAhUpd8Wpg)

Clique na imagem acima para assistir ao vídeo completo no YouTube, onde apresento a interface em funcionamento, a arquitetura visual e os conceitos de manipulação de memória e engenharia reversa aplicados.

## 🚀 Tecnologias e Conceitos Utilizados
* **Linguagem C++:** Desenvolvimento robusto de baixo nível focado em performance.
* **Dear ImGui:** Interface gráfica (GUI) leve, rápida e otimizada para ferramentas de debug e instrumentação.
* **Engenharia Reversa:** Análise de estruturas de dados, mapeamento de memória e modificação de comportamento de binários (Kernel Mod).

* ================================================================================
HOPLITA ENGINE — OFFICIAL PROJECT PRESENTATION
ENGLISH VERSION | BRAZILIAN TECHNOLOGY
================================================================================

Developer: Engineer Lucas Guilherme Bandeira — Brazil
Date: October 10, 2026

1. WHAT IS HOPLITA ENGINE?

Hoplita Engine is a Brazilian platform for memory analysis, debugging,
process monitoring, and trainer development, built in C++ for Windows.
The project brings together advanced tools in a modern, customizable
interface, supporting technical investigation, automation, and the study
of how applications and games operate.

Its purpose is to combine software engineering and low-level programming
features in a single environment for developers, researchers, students,
and technology enthusiasts.

2. MAIN FEATURES

MEMORY SCANNER
Search, identification, monitoring, and editing of values in accessible
processes, subject to operating-system permissions.

POINTER SCANNER
Investigation of pointer chains and dynamic addresses to understand how
applications organize data in memory.

DEBUGGER AND DISASSEMBLER
Tools to observe memory accesses, examine machine instructions, monitor
program execution, and investigate process behavior. Includes memory
viewing and visual instruction highlighting.

STRUCTURES AND COORDINATES
Inspection and organization of data structures, including analysis of
values related to positions and coordinates in three-dimensional spaces.

LUA AND SCRIPTS
Support for creating and running custom routines to extend and automate
operations within the tool.

TRAINER GENERATOR
Creation of trainers with customizable interfaces, activation controls,
icons, colors, visual effects, images, videos, game information, and
presentation settings. The project includes pointer and script options.

PROCESS MANAGEMENT
Selection of running processes and tools for identifying and monitoring
applications.

GRAPHICAL INTERFACE
Built with Dear ImGui, with organized panels, visual customization,
accessibility-oriented features, and Portuguese/English language support.

ADDITIONAL TOOLS
Memory inspection, technical visualization, automation, and integration
with operating-system-specific components.

3. USER MODE AND KERNEL MODE ARCHITECTURE

Hoplita Engine has an architecture covering two operating levels.

USER MODE — PUBLIC EDITION
Provides tools compatible with ordinary Windows permissions, without
requiring installation of a proprietary kernel driver.

KERNEL MODE — DEVELOPMENT ENVIRONMENT
The project also includes a Windows driver developed with WDK/KMDF for
communication and specific kernel-level memory operations. This
component is reserved for the development environment and is not
included in public distribution, as broad driver distribution requires
Microsoft's applicable signing and validation processes.

The kernel component does not imply unrestricted access to every process
or guaranteed compatibility with third-party protection mechanisms.

4. OFFLINE AND ONLINE GAMES

Hoplita Engine can analyze and modify data in game processes when the
operating system and the software's protections allow it. This includes
offline scenarios and, technically, certain online scenarios.

Operation is not guaranteed in every game. Anti-cheat systems,
permissions, updates, and publishers' rules may restrict or prevent use.

RESPONSIBLE USE NOTICE:
We do not recommend using Hoplita Engine to gain unfair advantages in
online matches, interfere with competitive environments, circumvent
protections, or violate gaming services' terms. Such practices may lead
to account restrictions, bans, or other consequences. The tool should
be used responsibly and with appropriate authorization.

5. PROJECT TECHNOLOGIES

- C++ as the main programming language;
- Dear ImGui for the graphical interface;
- Win32 APIs and native Windows functionality;
- Visual Studio for development and compilation;
- Windows Driver Kit (WDK) and KMDF for the kernel component;
- Lua for scripting and automation;
- Inno Setup for packaging and installation;
- Additional components and libraries used by project modules.

6. EDITIONS AND DISTRIBUTION

HOPLITA ENGINE PUBLIC
Distribution edition with User Mode functionality and clear information
that the kernel driver is not included in the installer.

HOPLITA ENGINE DEVELOPER
Development and testing environment, including technical components and
the kernel driver configured for the developer's authorized computer.

Publication in the Microsoft Store is under consideration and depends
on the platform's certification rules. Approval is not guaranteed.

7. CROSS-PLATFORM EXPANSION

WINDOWS — ORIGINAL PLATFORM
The project's main foundation, featuring its C++ tools and Dear ImGui
interface.

LINUX — PORT IN DEVELOPMENT
The Linux edition is being prepared to reuse portable components and
adapt Windows-dependent functions to native process, memory, debugging,
and interface mechanisms. Any Linux kernel module must be separately
developed and validated for that platform.

ANDROID — FUTURE PLAN
An Android edition is being considered, with an interface and features
adapted to the mobile system's permissions, security restrictions, and
architectures. Immediate feature parity with Windows is not promised.

8. IDENTITY AND PURPOSE

Hoplita Engine is a Brazilian technology initiative focused on memory
analysis, software engineering, debugging, and specialized tool creation.

Its goal is continuous development, emphasizing performance, source-code
organization, documentation, modern features, and responsible use.

HOPLITA ENGINE
Brazilian Technology • Advanced Engineering • Innovation and Development

Developer: Engineer Lucas Guilherme Bandeira
Country of origin: Brazil

TRANSPARENCY NOTE
This presentation describes the project's known features and goals.
Actual feature availability depends on the edition, version, environment,
and completed testing. Linux and Android are development plans, not
finished releases.


================================================================================
HOPLITA ENGINE — APRESENTAÇÃO OFICIAL DO PROJETO
VERSÃO EM PORTUGUÊS | TECNOLOGIA BRASILEIRA
================================================================================

Desenvolvedor: Engenheiro Lucas Guilherme Bandeira — Brasil
Data: 10 de outubro de 2026

1. O QUE É O HOPLITA ENGINE?

O Hoplita Engine é uma plataforma brasileira de análise de memória,
depuração, monitoramento de processos e desenvolvimento de trainers,
criada em C++ para o ambiente Windows. O projeto reúne ferramentas
avançadas em uma interface gráfica moderna e personalizável, buscando
oferecer recursos de investigação técnica, automação e estudo do
funcionamento de programas e jogos.

Sua proposta é unir funcionalidades de engenharia de software e
programação de baixo nível em um único ambiente, com recursos destinados
a desenvolvedores, pesquisadores, estudantes e entusiastas de tecnologia.

2. PRINCIPAIS FUNCIONALIDADES

SCANNER DE MEMÓRIA
Pesquisa, identificação, monitoramento e edição de valores em processos
acessíveis, respeitando as permissões do sistema operacional.

POINTER SCANNER
Investigação de cadeias de ponteiros e endereços dinâmicos para
compreender como aplicações organizam seus dados em memória.

DEBUGGER E DISASSEMBLER
Ferramentas para observar acessos à memória, examinar instruções de
máquina, acompanhar a execução de programas e investigar comportamentos
de processos. Inclui recursos de visualização de memória e destaque
visual de instruções.

STRUCTURES E COORDENADAS
Inspeção e organização de estruturas de dados, incluindo análise de
valores associados a posições e coordenadas em ambientes tridimensionais.

LUA E SCRIPTS
Suporte à criação e execução de rotinas personalizadas para ampliar e
automatizar operações dentro da ferramenta.

GERADOR DE TRAINERS
Criação de trainers com interface personalizada, opções de ativação,
ícones, cores, efeitos visuais, imagens, vídeos, informações do jogo e
opções de apresentação. O projeto contempla configurações de ponteiros
e scripts.

GERENCIAMENTO DE PROCESSOS
Seleção de processos em execução e recursos de identificação e
acompanhamento de aplicações.

INTERFACE GRÁFICA
Interface desenvolvida com Dear ImGui, com organização de painéis,
opções de personalização visual, recursos de acessibilidade e suporte
aos idiomas português e inglês.

FERRAMENTAS COMPLEMENTARES
Recursos de inspeção de memória, visualização técnica, automação e
integração com componentes específicos do sistema operacional.

3. ARQUITETURA USER MODE E KERNEL MODE

O Hoplita Engine foi desenvolvido com uma arquitetura que contempla
dois níveis de operação.

USER MODE — EDIÇÃO PÚBLICA
Permite executar as ferramentas compatíveis com as permissões normais
do Windows, sem exigir a instalação de um driver Kernel próprio.

KERNEL MODE — AMBIENTE DE DESENVOLVIMENTO
O projeto também possui um driver Windows desenvolvido com WDK/KMDF
para comunicação e operações específicas de memória em nível de Kernel.
Esse componente permanece reservado ao ambiente de desenvolvimento e
não acompanha a distribuição pública, pois a distribuição geral de
drivers exige os processos adequados de assinatura e validação da
Microsoft.

A existência do componente Kernel não representa acesso irrestrito a
qualquer processo nem compatibilidade garantida com mecanismos de
proteção de terceiros.

4. JOGOS OFFLINE E ONLINE

O Hoplita Engine pode analisar e modificar dados de processos de jogos
quando o sistema operacional e as proteções do software permitem.
Isso inclui cenários offline e, tecnicamente, determinados cenários online.

O funcionamento não é garantido em todos os jogos. Sistemas anti-cheat,
permissões, atualizações e regras das produtoras podem limitar ou
impedir o uso.

AVISO DE USO RESPONSÁVEL:
Não recomendamos utilizar o Hoplita Engine para obter vantagens
indevidas em partidas online, interferir em ambientes competitivos,
contornar proteções ou violar os termos de serviços de jogos. Essas
práticas podem provocar bloqueios de conta, banimentos e outras
consequências. A ferramenta deve ser utilizada com responsabilidade
e autorização adequada.

5. TECNOLOGIAS DO PROJETO

- C++ como linguagem principal;
- Dear ImGui para interface gráfica;
- APIs Win32 e recursos nativos do Windows;
- Visual Studio para desenvolvimento e compilação;
- Windows Driver Kit (WDK) e KMDF no componente Kernel;
- Lua para scripts e automações;
- Inno Setup para empacotamento e instalação;
- Componentes e bibliotecas complementares utilizados pelos módulos
  do projeto.

6. EDIÇÕES E DISTRIBUIÇÃO

HOPLITA ENGINE PUBLIC
Edição destinada à distribuição, com funcionalidades disponíveis em
User Mode e informação clara de que o driver Kernel não acompanha
o instalador.

HOPLITA ENGINE DEVELOPER
Ambiente de desenvolvimento e testes, incluindo os componentes técnicos
e o driver Kernel configurado para o computador autorizado do desenvolvedor.

A publicação na Microsoft Store é uma possibilidade em avaliação e
dependerá das regras de certificação da plataforma. Não existe
aprovação garantida.

7. EXPANSÃO MULTIPLATAFORMA

WINDOWS — PLATAFORMA ORIGINAL
É a base principal do projeto, com o conjunto de ferramentas
desenvolvido em C++ e interface Dear ImGui.

LINUX — PORTABILIDADE EM DESENVOLVIMENTO
A versão Linux está sendo preparada para aproveitar os componentes
portáveis do projeto e adaptar as funções dependentes do Windows a
mecanismos nativos de processos, memória, depuração e interface.
Um eventual módulo Kernel Linux precisará ser desenvolvido e validado
especificamente para essa plataforma.

ANDROID — PLANEJAMENTO FUTURO
Há planos de estudar uma edição Android, com interface e recursos
compatíveis com as permissões, restrições e arquiteturas do sistema
móvel. Não há promessa de paridade imediata com o Windows.

8. IDENTIDADE E PROPÓSITO

O Hoplita Engine representa uma iniciativa brasileira de desenvolvimento
tecnológico voltada à análise de memória, engenharia de software,
depuração e criação de ferramentas especializadas.

Seu objetivo é evoluir de forma contínua, valorizando desempenho,
organização do código-fonte, documentação, recursos modernos e
desenvolvimento responsável.

HOPLITA ENGINE
Tecnologia brasileira • Engenharia avançada • Inovação e desenvolvimento

Desenvolvedor: Engenheiro Lucas Guilherme Bandeira
País de origem: Brasil

NOTA DE TRANSPARÊNCIA
Esta apresentação descreve os recursos e objetivos conhecidos do projeto.
A disponibilidade efetiva de cada função depende da edição, versão,
ambiente e testes realizados. Linux e Android são planos de
desenvolvimento, não versões finais já concluídas.
