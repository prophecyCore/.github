# ProphecyCore

**ProphecyCore** é a organização responsável pelo desenvolvimento e manutenção do projeto **Prophecy**, uma ferramenta voltada para automatizar a criação de testes unitários (TUs) para aplicações Angular, utilizando Karma e Jasmine, com base em classes. O objetivo é facilitar a criação de testes unitários, permitindo que os desenvolvedores foquem na parte lógica dos testes, enquanto a ferramenta cuida da configuração inicial e da resolução de dependências.

## Objetivos do Projeto

O **Prophecy** visa oferecer uma solução inteligente para a criação de testes unitários. Atualmente, a ferramenta consegue gerar a base do teste unitário para classes Angular, resolvendo as dependências do construtor e permitindo que o desenvolvedor adicione facilmente os *its* (testes unitários). A longo prazo, o projeto pretende:

- Ampliar o suporte para outros frameworks JavaScript.
- Incluir compatibilidade com bibliotecas de teste como Jest e outras.
- Evoluir para a geração de *its* completos, aumentando a cobertura de testes.
- **Suporte a múltiplas linguagens de programação**, além de JavaScript/TypeScript, incluindo as mais populares no mercado, como Python, Java, Ruby, entre outras.

## Funcionalidades

- **Geração Automática de Testes Unitários**: Criação da estrutura básica de testes para classes Angular, com dependências do construtor já resolvidas.
- **Integração com VSCode**: Disponibilidade como uma extensão para o editor de código Visual Studio Code, permitindo gerar rapidamente a base dos testes diretamente no ambiente de desenvolvimento.
- **Futuro Suporte a CLI**: Transformação do projeto em uma ferramenta de linha de comando (CLI), permitindo seu uso fora do VSCode.

## Visão de Futuro

A longo prazo, o **Prophecy** pretende se tornar uma ferramenta robusta e amplamente adotada para criação de testes unitários, com o objetivo de facilitar o trabalho dos desenvolvedores e aumentar a cobertura de testes em projetos de qualquer escala.

Além disso, há a intenção de expandir a ferramenta para ser compatível com outras bibliotecas de testes, como Jest, e até com outros frameworks JavaScript, proporcionando uma solução mais flexível e escalável.

### Planos de Expansão

- **Suporte a outras bibliotecas de testes**: Ampliar a compatibilidade com Jest e outras bibliotecas de testes populares.
- **Geração de *its***: Desenvolver a capacidade de gerar automaticamente os *its* para os testes, aumentando a cobertura e a qualidade dos testes.
- **Compatibilidade com Outras Linguagens**: A longo prazo, expandir o **Prophecy** para suportar não só JavaScript e TypeScript, mas também outras linguagens de programação populares, como Python, Java, Ruby, e mais.

## Considerações Importantes

### 1. Testes Unitários: Não Estamos Driblando a Qualidade!

Uma das críticas que o **Prophecy** pode enfrentar é que, ao automatizar a criação dos testes, a qualidade do código de teste pode ser comprometida. Porém, o objetivo do **Prophecy** não é substituir o trabalho do desenvolvedor, mas agilizar a criação da estrutura básica de testes, garantindo que o desenvolvedor possa se concentrar na parte lógica dos testes, mantendo a qualidade.

### 2. IA Generativa: Não Seria Possível Usar IA para Isso?

Embora ferramentas baseadas em IA possam gerar testes unitários, existem cenários em que o uso de IA não é viável devido a questões de segurança, confidencialidade ou licenciamento. O **Prophecy** não depende de IA para gerar os testes. Em vez disso, ele usa algoritmos para ler o código e gerar os testes de maneira segura e eficiente, sem a necessidade de enviar dados para servidores externos.

## Como Contribuir

1. Fork o repositório.
2. Crie uma branch para sua feature ou correção (`git checkout -b feature/nova-feature`).
3. Faça suas modificações e commit (`git commit -am 'Adicionando nova feature'`).
4. Push para a branch (`git push origin feature/nova-feature`).
5. Abra um Pull Request.

## Licença

Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.

---

**ProphecyCore** - Facilitando a criação de testes unitários de maneira inteligente e escalável, com foco na produtividade dos desenvolvedores e a qualidade do código!
