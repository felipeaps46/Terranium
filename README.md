<div align="center">
  
# 🌿 Terranium

### Documentação de Arquitetura de Software 

[![Arquitetura](https://img.shields.io/badge/Arquitetura-OK-1B4F72?style=for-the-badge&logo=buffer&logoColor=white)]()
[![UML](https://img.shields.io/badge/UML-Diagramas-2C3E50?style=for-the-badge&logo=uml&logoColor=white)]()
[![PlantUML](https://img.shields.io/badge/PlantUML-Source-145A32?style=for-the-badge&logo=uml&logoColor=white)]()
[![Docs](https://img.shields.io/badge/Docs-Disponível-6E2C00?style=for-the-badge&logo=mdbook&logoColor=white)]()

</div>

## 🚀 Bem-vindo(a) à documentação do Projeto Terranium!

Este repositório serve como um hub central para toda a documentação de arquitetura, design e modelagem do software Terranium. Aqui, você encontrará uma coleção abrangente de diagramas UML e outros artefatos visuais que detalham a estrutura, o comportamento e as interações do sistema, fornecendo uma visão clara e estruturada para todos os stakeholders envolvidos.

---

## 📚 Índice

*   [Visão Geral da Documentação](#-visão-geral-da-documentação)
*   [Diagrama de Arquitetura](#-diagrama-de-arquitetura)
*   [Diagrama de Caso de Uso](#-diagrama-de-caso-de-uso)
*   [Diagrama de Classe](#-diagrama-de-classe)
*   [Diagrama de Componentes](#-diagrama-de-componentes)
*   [Diagramas de Comunicação](#-diagramas-de-comunicação)
    *   [Comunicação: Cadastro de Propriedade (UC-04)](#diagrama-de-comunicação-cadastro-de-propriedade-uc-04)
    *   [Comunicação: Planejar Safra (UC-10)](#diagrama-de-comunicação-planejar-safra-uc-10)
    *   [Comunicação: Cadastrar Observações de Campo (UC-15)](#diagrama-de-comunicação-cadastrar-observações-de-campo-uc-15)
*   [Diagrama de Estados](#-diagrama-de-estados)
*   [Diagrama de Implantação](#-diagrama-de-implantação)
*   [Diagrama de Modelo de Dados](#-diagrama-de-modelo-de-dados)
*   [Diagramas de Sequência](#-diagramas-de-sequência)
    *   [Sequência: Cadastro de Propriedade (UC-04)](#diagrama-de-sequência-cadastro-de-propriedade-uc-04)
    *   [Sequência: Planejar Safra (UC-10)](#diagrama-de-sequência-planejar-safra-uc-10)
    *   [Sequência: Cadastrar Observações de Campo (UC-15)](#diagrama-de-sequência-cadastrar-observações-de-campo-uc-15)
    *   [Sequência: Sistema Geral](#diagrama-de-sequência-sistema-geral)

---

## 💡 Visão Geral da Documentação

Cada seção abaixo contém um diagrama específico acompanhado de uma breve descrição do seu propósito e do que ele representa no contexto do sistema Terranium.

---

## Diagrama de Arquitetura

Este diagrama ilustra a estrutura de alto nível do sistema Terranium, mostrando os principais componentes, módulos e suas interações fundamentais. Ele fornece uma visão macro da organização do software.

![Diagrama de Arquitetura](https://github.com/felipeaps46/Terranium/blob/main/Imagens/DiagramaArquitetura.png?raw=true)

---

## Diagrama de Caso de Uso

Apresenta os casos de uso principais do sistema Terranium, identificando os atores (usuários, sistemas externos) e as funcionalidades que eles podem executar, descrevendo o comportamento externo do sistema.

![Diagrama de Caso de Uso](https://github.com/felipeaps46/Terranium/blob/main/Imagens/DiagramaCasoDeUso.png?raw=true)

---

## Diagrama de Classe

Detalha as classes do sistema, seus atributos, métodos e os relacionamentos estáticos (associações, heranças, agregações, composições) entre elas, representando a estrutura estática do projeto.

![Diagrama de Classe](https://github.com/felipeaps46/Terranium/blob/main/Imagens/DiagramaClasse.png?raw=true)

---

## Diagrama de Componentes

Exibe a organização e a dependência dos componentes de software, fornecendo uma visão modular do sistema e como as diferentes partes lógicas se encaixam e interagem.

![Diagrama de Componentes](https://github.com/felipeaps46/Terranium/blob/main/Imagens/DiagramaComponentes.png?raw=true)

---

## Diagramas de Comunicação

Estes diagramas mostram a interação entre objetos e componentes em um determinado cenário, focando na troca de mensagens e na colaboração para atingir um objetivo específico.

### Diagrama de Comunicação: Cadastro de Propriedade (UC-04)

Detalha as interações necessárias para o processo de cadastro de uma nova propriedade rural no sistema Terranium.

![Diagrama de Comunicação - Cadastro de Propriedade (UC-04)](https://github.com/felipeaps46/Terranium/blob/main/Imagens/DiagramaComunicacao(CadastroPropriedade).png?raw=true)

### Diagrama de Comunicação: Planejar Safra (UC-10)

Detalha as interações dos componentes do sistema para o planejamento de uma safra, desde a seleção de culturas e áreas até a persistência do plano.

![Diagrama de Comunicação - Planejar Safra (UC-10)](https://github.com/felipeaps46/Terranium/blob/main/Imagens/DiagramaComunicacao(PlanejarSafra).png?raw=true)

### Diagrama de Comunicação: Cadastrar Observações de Campo (UC-15)

Ilustra o fluxo de mensagens entre os objetos para registrar observações de campo, incluindo a possibilidade de anexar mídias.

![Diagrama de Comunicação - Cadastrar Observações de Campo (UC-15)](https://github.com/felipeaps46/Terranium/blob/main/Imagens/DiagramaComunicacao(CadastrarObservacoesCampo).png?raw=true)

---

## 🔄 Diagrama de Estados

Representa os diferentes estados que um objeto ou parte do sistema pode ter ao longo do tempo e as transições entre esses estados em resposta a eventos específicos.

![Diagrama de Estados](https://github.com/felipeaps46/Terranium/blob/main/Imagens/DiagramaEstados.png?raw=true)

---

## 🚀 Diagrama de Implantação

Descreve a configuração física de hardware onde o software será executado, incluindo os nós (servidores, dispositivos) e os componentes de software implantados neles.

![Diagrama de Implantação](https://github.com/felipeaps46/Terranium/blob/main/Imagens/DiagramaImplantacao.png?raw=true)

---

## 💾 Diagrama de Modelo de Dados

Ilustra a estrutura lógica do banco de dados, mostrando as entidades, seus atributos e os relacionamentos entre elas, essencial para a persistência de informações do sistema.

![Diagrama de Modelo de Dados](https://github.com/felipeaps46/Terranium/blob/main/Imagens/DiagramaModeloDeDados.png?raw=true)

---

## ⏳ Diagramas de Sequência

Estes diagramas detalham a ordem cronológica das interações e a troca de mensagens entre objetos ou atores para realizar uma funcionalidade específica, mostrando a vida útil de cada participante.

### Diagrama de Sequência: Cadastro de Propriedade (UC-04)

Representa o fluxo de eventos e mensagens para o cadastro de uma nova propriedade.

![Diagrama de Sequência - Cadastro de Propriedade](https://github.com/felipeaps46/Terranium/blob/main/Imagens/DiagramaSequencia(CadastroPropriedade).png?raw=true)

### Diagrama de Sequência: Planejar Safra (UC-10)

Mostra a sequência de interações para o processo de planejamento de safra.

![Diagrama de Sequência - Planejar Safra](https://github.com/felipeaps46/Terranium/blob/main/Imagens/DiagramaSequencia(PlanejarSafra).png?raw=true)

### Diagrama de Sequência: Cadastro de Observações de Campo

Ilustra o fluxo de eventos e mensagens para o cadastro de uma nova observação de campo.

![Diagrama de Sequência - Acesso Geral a Funcionalidades](https://github.com/felipeaps46/Terranium/blob/main/Imagens/DiagramaSequencia(CadastroObservacoesCampo).png?raw=true)

### Diagrama de Sequência: Sistema Geral

Oferece uma visão mais ampla das principais interações e fluxo de controle em um cenário genérico do sistema.

![Diagrama de Sequência - Sistema Geral](https://github.com/felipeaps46/Terranium/blob/main/Imagens/DiagramaSequencia(Sistema).png?raw=true)


---

## 🗺️ Como Navegar

Utilize o índice no início deste `README` para pular diretamente para o diagrama de interesse. Cada diagrama possui uma breve descrição para contextualizar seu propósito no Projeto Terranium.

## 🤝 Contribuições

Se você identificar alguma inconsistência, tiver sugestões para melhorar a documentação ou desejar adicionar novos diagramas, sinta-se à vontade para abrir uma *issue* ou enviar um *pull request* neste repositório. Sua colaboração é muito bem-vinda!

---

Desenvolvido com 💚 para o Projeto Terranium.
