# Prophecy

**Prophecy** é uma ferramenta inovadora focada em automatizar a criação de testes unitários para Angular, com Karma e Jasmine, a partir de classes. O projeto tem a ambição de, no futuro, expandir sua compatibilidade para outras bibliotecas de teste, como Jest, e suportar diversos frameworks JavaScript.

Atualmente, **Prophecy** é uma extensão do VSCode, mas há planos de transformá-la também em uma ferramenta de linha de comando (CLI) para tornar o processo mais flexível e independente do editor de texto.

## Objetivos

O objetivo principal do **Prophecy** é fornecer uma maneira simples e eficiente de gerar a base para os testes unitários (TUs) de aplicações Angular, resolvendo automaticamente as dependências do construtor, permitindo que o desenvolvedor se concentre apenas na criação dos *its* (os testes unitários).

A visão de longo prazo do projeto inclui:

- Criar testes unitários para outros frameworks JavaScript, além do Angular.
- Suporte para mais bibliotecas de testes, como Jest.
- Capacidade de gerar *its* completos com boa cobertura de testes, aumentando a eficiência e a produtividade dos desenvolvedores.

## Funcionalidades Atuais

- **Geração Automática de Testes Unitários**: Gera a estrutura básica do teste unitário (arquivo `.spec.ts`) para uma classe Angular, com as dependências do construtor já resolvidas.
- **Extensão VSCode**: Integração com o Visual Studio Code, permitindo gerar os testes diretamente do editor de texto.
  
## Funcionalidades Futuras

- **Geração de *its* de Teste**: Desenvolvimento de funcionalidades que permitam a criação de *its* básicos e até mesmo parte da lógica de teste, com a meta de alcançar maior cobertura de testes.
- **Suporte para Jest e outras bibliotecas de teste**: Expansão do suporte para frameworks de teste além de Karma e Jasmine, como Jest, para atender a uma gama maior de projetos JavaScript.
- **CLI (Interface de Linha de Comando)**: Transformação da ferramenta em uma CLI, para que possa ser usada de forma independente do editor de código, facilitando sua integração com outros ambientes de desenvolvimento.

## Como Usar

### Como Extensão VSCode

1. Instale a extensão **Prophecy** no VSCode.
2. Abra o arquivo da classe Angular que você deseja criar os testes.
3. Execute o comando da extensão para gerar a estrutura básica do teste unitário.
4. Complete os *its* no arquivo gerado para testar sua lógica.

### Como CLI (Futuro)

1. Instale a CLI do Prophecy globalmente.
2. Execute o comando para gerar a base do teste unitário a partir de uma classe Angular.
3. Complete os *its* no arquivo gerado.

## Como Contribuir

1. Fork o repositório.
2. Crie uma branch para sua feature ou correção (`git checkout -b feature/nova-feature`).
3. Faça suas modificações e commit (`git commit -am 'Adicionando nova feature'`).
4. Push para a branch (`git push origin feature/nova-feature`).
5. Abra um Pull Request.

## Licença

Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.

---

**Prophecy** - Automatizando o futuro dos testes unitários em Angular e mais!
