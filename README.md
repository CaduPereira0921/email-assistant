# Email Assistant com Memória Semântica, Episódica e Procedural 

Este repositório contém o notebook Jupyter da Lição 5 de um projeto de assistente de e-mail. Este assistente utiliza Modelos de Linguagem (LLMs) com funcionalidades avançadas de memória para triagem, resposta automática e agendamento de reuniões.

## Visão Geral

O objetivo principal deste notebook é explorar e demonstrar a implementação de diferentes tipos de memória em um assistente de e-mail:

* **Memória Semântica**: Para armazenar e recuperar informações gerais e conhecimento de longo prazo.
* **Memória Episódica**: Para lembrar detalhes e contexto de interações passadas com e-mails.
* **Memória Procedural**: Para permitir a atualização dinâmica das instruções e regras que guiam o comportamento do assistente e suas ferramentas (como agendamento de calendário e escrita de e-mails).

## Conteúdo

* **`lesson_5.ipynb`**: O notebook principal que contém o código, explicações e demonstrações da construção e funcionamento do assistente de e-mail com as capacidades de memória.

## Como Usar o Notebook

Para explorar este projeto, você precisará ter o Jupyter Notebook ou Jupyter Lab instalado, juntamente com as bibliotecas Python necessárias.

### Pré-requisitos

* Python 3.9+
* Jupyter Notebook / Jupyter Lab
* Chaves de API para os Modelos de Linguagem (ex: OpenAI, Anthropic) configuradas como variáveis de ambiente.

### Instalação e Execução

1.  **Clone este repositório** (se você ainda não o fez, mas como você já enviou, este passo é mais para outros usuários):
    ```bash
    git clone [https://github.com/CaduPereira0921/email-assistant.git](https://github.com/CaduPereira0921/email-assistant.git)
    cd email-assistant
    ```
    *Como você já enviou, você já tem o repositório local. Este passo é mais para quem for clonar.*

2.  **Abra o notebook com Jupyter Lab/Notebook**:
    ```bash
    jupyter lab lesson_5.ipynb
    # ou
    jupyter notebook lesson_5.ipynb
    ```

3.  **Instale as dependências**: Dentro do notebook, geralmente há células que instalam as dependências (`pip install ...`). Certifique-se de executar essas células. As principais bibliotecas provavelmente incluem `langgraph`, `langchain`, `langmem`, `python-dotenv`, e bibliotecas dos provedores de LLM como `openai` e `anthropic`.

4.  **Configure suas variáveis de ambiente**: Para o notebook funcionar, você provavelmente precisará configurar suas chaves de API. Crie um arquivo `.env` na raiz do seu projeto (no mesmo nível do `lesson_5.ipynb` e do `README.md`) e adicione suas chaves:

    ```
    # .env
    OPENAI_API_KEY=sua_chave_openai_aqui
    ANTHROPIC_API_KEY=sua_chave_anthropic_aqui
    ```
    **AVISO**: Não adicione o arquivo `.env` ao controle de versão do Git! Ele deve ser ignorado. Se você ainda não tem um `.gitignore`, pode criar um e adicionar `.env` nele. (Vou te dar os passos para isso logo após o README).

5.  **Execute as células do notebook**: Siga as instruções e execute as células do `lesson_5.ipynb` para ver o assistente em ação.

## Contribuição

Este repositório é principalmente para fins de aprendizado e demonstração. Se tiver sugestões ou encontrar problemas, sinta-se à vontade para abrir uma issue.

## Licença

Este projeto não possui uma licença explícita definida no momento. O uso do código é de responsabilidade do usuário.
(Considerar adicionar uma licença de código aberto, como MIT ou Apache 2.0, se você planeja que outros usem e contribuam com seu código.)

---

**Cadu Pereira**
