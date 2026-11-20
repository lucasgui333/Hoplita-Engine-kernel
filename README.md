# HOPLITA ENGINE 🛠️

**Tecnologia brasileira | C++ | Dear ImGui | Engenharia reversa**

![Hoplita Engine — Lançamento Público](assets/hoplita-lancamento.jpg)

## 📺 Demonstração oficial / Official demonstration

[![Assistir ao vídeo do Hoplita Engine](https://img.youtube.com/vi/AImQ5s2WIRY/hqdefault.jpg)](https://youtu.be/AImQ5s2WIRY)

**Vídeo:** https://youtu.be/AImQ5s2WIRY

---

## 🇧🇷 Apresentação oficial — Português

O **Hoplita Engine** é uma plataforma brasileira de análise de memória, depuração, monitoramento de processos e desenvolvimento de trainers, desenvolvida em **C++** para Windows, com interface em **Dear ImGui**.

### Funcionalidades e módulos

- **Scanner de memória:** pesquisa, monitoramento e edição de valores em processos acessíveis.
- **Pointer Scanner:** análise de cadeias de ponteiros e endereços dinâmicos.
- **Debugger e Disassembler:** investigação de instruções, acessos à memória e execução.
- **Structures e Coordenadas:** inspeção de estruturas e valores associados a posições 3D.
- **Lua e Scripts:** rotinas personalizadas e automação.
- **Gerador de Trainers:** criação de interfaces, controles, ícones, cores, imagens, vídeos e scripts.
- **Gerenciamento de Processos:** seleção e acompanhamento de aplicações.
- **Interface personalizável:** painéis organizados e suporte a português/inglês.

### Arquitetura e edições

**Hoplita Engine Public — User Mode:** edição de distribuição pública, sem driver Kernel próprio no instalador.

**Hoplita Engine Developer — Kernel Mode:** ambiente de desenvolvimento e testes, com componente Windows WDK/KMDF reservado a máquinas autorizadas. A distribuição de drivers exige assinatura e validação aplicáveis. A existência desse componente não garante acesso irrestrito nem compatibilidade com mecanismos de proteção de terceiros.

### Tecnologias

C++, Dear ImGui, Win32 API, Visual Studio, WDK/KMDF, Lua e Inno Setup, além das bibliotecas dos módulos.

### Plataformas

- **Windows:** plataforma original.
- **Linux:** portabilidade em desenvolvimento; funcionalidades dependentes do Windows precisam de adaptação nativa.
- **Android:** possibilidade futura, sujeita às permissões e restrições da plataforma.

### Uso responsável

A análise ou modificação de processos depende de permissões, proteções e regras aplicáveis. O uso em jogos online pode ser restrito por sistemas anti-cheat e termos de serviço. Não recomendamos vantagens indevidas em partidas competitivas, contorno de proteções ou uso sem autorização.

---

## 🇺🇸 Official project presentation — English

**Hoplita Engine** is a Brazilian platform for memory analysis, debugging, process monitoring, and trainer development. It is built in **C++** for Windows and uses **Dear ImGui** for its graphical interface.

### Features and modules

- **Memory Scanner:** search, monitor, and edit values in accessible processes.
- **Pointer Scanner:** investigate pointer chains and dynamic addresses.
- **Debugger and Disassembler:** inspect instructions, memory accesses, and execution behavior.
- **Structures and Coordinates:** explore data structures and 3D position-related values.
- **Lua and Scripts:** custom routines and automation.
- **Trainer Generator:** customizable controls, icons, colors, images, videos, and scripts.
- **Process Management:** select and monitor running applications.
- **Customizable GUI:** organized panels and Portuguese/English support.

### Architecture and editions

**Hoplita Engine Public — User Mode:** public distribution edition; no proprietary kernel driver is included in its installer.

**Hoplita Engine Developer — Kernel Mode:** development and testing environment with a Windows WDK/KMDF component reserved for authorized machines. Driver distribution is subject to applicable signing and validation requirements. Kernel functionality does not guarantee unrestricted access or compatibility with third-party protections.

### Technologies

C++, Dear ImGui, Win32 APIs, Visual Studio, WDK/KMDF, Lua, Inno Setup, and additional module libraries.

### Platforms

- **Windows:** original platform.
- **Linux:** port in development; Windows-specific features require native adaptations.
- **Android:** future possibility, subject to platform permissions and restrictions.

### Responsible use

Memory analysis and modification depend on permissions, software protections, and applicable rules. Online games may restrict such tools through anti-cheat systems and terms of service. We do not recommend unfair competitive advantages, bypassing protections, or unauthorized use.

---

## 👨‍💻 Créditos / Credits

**Desenvolvedor / Developer:** Lucas Guilherme Bandeira  
**Origem / Origin:** Brasil / Brazil  
**Projeto / Project:** Hoplita Engine

> **Nota de transparência / Transparency note:** A disponibilidade das funcionalidades depende da edição, versão e testes concluídos. Feature availability depends on edition, version, and completed testing. Linux and Android are not presented as completed releases.
