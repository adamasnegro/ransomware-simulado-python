# 🔐 Ransomware Simulado com Python — Laboratório de Cibersegurança

## 📌 Sobre o Projeto

Este projeto consiste no desenvolvimento de um laboratório educacional de simulação de Ransomware utilizando a linguagem Python, realizado como parte do **BootCamp Santander — Cibersegurança do Zero à Prática**, oferecido pela plataforma DIO (Digital Innovation One).

O laboratório tem como finalidade demonstrar, em ambiente controlado, o funcionamento básico de um Ransomware por meio da criação de arquivos de teste, implementação de scripts para criptografia e descriptografia e geração de uma mensagem simulada de resgate.

Durante o experimento, foram utilizados dois arquivos de teste, denominados `dados-confidenciais` e `senhas`, armazenados na pasta `test_file`.

O projeto possui dois scripts principais:

- `ransomware.py`: responsável pelo processo de criptografia dos arquivos de teste.
- `descriptografar.py`: responsável pelo processo de descriptografia e recuperação dos arquivos.

O desenvolvimento permitiu compreender conceitos relacionados à criptografia, funcionamento de malwares, indisponibilidade de dados e estratégias de proteção contra ameaças digitais.

## 🎯 Objetivos de Aprendizagem

Ao concluir este desafio, foram desenvolvidas as seguintes competências:

- Compreender o funcionamento prático de um Ransomware.
- Identificar como malwares exploram vulnerabilidades técnicas e brechas humanas.
- Programar scripts em Python para simular comportamentos de ataques em ambiente controlado.
- Compreender os processos de criptografia e descriptografia de arquivos.
- Analisar os riscos relacionados à indisponibilidade de dados.
- Refletir sobre estratégias de defesa e prevenção contra malwares.
- Documentar experimentos técnicos utilizando Markdown.
- Utilizar Git e GitHub para versionamento e construção de portfólio técnico.

## 📚 Conteúdo do Módulo

O laboratório foi desenvolvido seguindo as seguintes etapas:

1. **Definir Malware e seus problemas**
   - Conceito de malware.
   - Impactos dos códigos maliciosos.
   - Riscos para sistemas e informações.

2. **Introdução**
   - Apresentação do funcionamento de um Ransomware.
   - Conceitos fundamentais relacionados à ameaça.

3. **Exemplos de Malware**
   - Tipos de códigos maliciosos.
   - Características e consequências dos ataques.

4. **Construindo nosso Ambiente**
   - Preparação do ambiente de desenvolvimento.
   - Criação dos arquivos utilizados nos testes.
   - Organização dos diretórios do laboratório.

5. **Criando as funções do Ransomware**
   - Implementação das funções de criptografia.
   - Implementação das funções de descriptografia.
   - Geração da mensagem simulada de resgate.

6. **Analisando os códigos das funções**
   - Análise da lógica dos scripts Python.
   - Compreensão do processo de transformação dos arquivos.

7. **Executando o Script e Criptografando os Arquivos**
   - Execução do arquivo `ransomware.py`.
   - Simulação da criptografia dos arquivos de teste.
   - Verificação dos arquivos após o procedimento.

8. **Descriptografando os Arquivos**
   - Execução do arquivo `descriptografar.py`.
   - Recuperação dos arquivos utilizados no laboratório.
   - Verificação dos dados restaurados.

## 🛠️ Tecnologias e Ferramentas

| Tecnologia / Ferramenta | Aplicação |
|---|---|
| Python | Desenvolvimento dos scripts de simulação |
| Criptografia | Transformação dos arquivos de teste |
| Descriptografia | Recuperação dos arquivos originais |
| Git | Controle de versão |
| GitHub | Hospedagem e documentação do projeto |
| DIO | Plataforma de aprendizagem |
| Windows | Ambiente de desenvolvimento |

## 📂 Estrutura do Projeto

A organização dos arquivos foi realizada da seguinte maneira:

```text
ransomware-simulado-python/
│
├── README.md
├── ransomware.py
├── descriptografar.py
├── chave.key
├── LEIA ISSO.txt
│
├── test_file/
│   ├── dados-confidenciais
│   └── senhas
│
└── img/
    ├── 01 - construindo_ambiente.png
    ├── 02 - construindo_ambiente.png
    ├── 03 - arquivos_criptografados.png
    └── 04 - dados_descriptografados.png
```

### Descrição dos arquivos

| Arquivo / Diretório | Descrição |
|---|---|
| `ransomware.py` | Script Python responsável por criptografar os arquivos de teste. |
| `descriptografar.py` | Script Python responsável por descriptografar e recuperar os arquivos. |
| `chave.key` | Arquivo de chave utilizado no laboratório. |
| `LEIA ISSO.txt` | Arquivo com instruções complementares do laboratório. |
| `test_file/` | Diretório contendo os arquivos utilizados no experimento. |
| `dados-confidenciais` | Primeiro arquivo utilizado na simulação. |
| `senhas` | Segundo arquivo utilizado na simulação. |
| `img/` | Diretório com as evidências visuais do laboratório. |

## 🖥️ Desenvolvimento do Laboratório

### 1. Construindo o Ambiente

Nesta etapa foi preparado o ambiente de desenvolvimento e organizada a estrutura necessária para a realização do experimento.

Foram criados os arquivos de teste que seriam utilizados durante os procedimentos de criptografia e descriptografia.

**Evidência 01 — Construção do ambiente**

![01 - Construindo o ambiente](img/01%20-%20construindo_ambiente.png)

**Evidência 02 — Preparação do ambiente**

![02 - Construindo o ambiente](img/02%20-%20construindo_ambiente.png)

### 2. Preparação dos Arquivos de Teste

Nesta etapa foi realizada a preparação dos arquivos que seriam utilizados na simulação.

Os arquivos `dados-confidenciais` e `senhas` foram organizados dentro do diretório `test_file`, servindo como dados de teste para demonstrar o funcionamento dos scripts desenvolvidos em Python.

### 3. Criptografando os Arquivos

Nesta etapa foi executado o script `ransomware.py`, responsável por realizar a simulação do processo de criptografia dos arquivos de teste.

O procedimento demonstrou como um Ransomware pode tornar informações indisponíveis para seus usuários.

Também foi apresentada uma mensagem simulada de resgate, representando uma característica comum desse tipo de ameaça.

**Evidência 03 — Arquivos criptografados**

![03 - Arquivos criptografados](img/03%20-%20arquivos_criptografados.png)

### 4. Descriptografando os Arquivos

Após a execução da simulação de criptografia, foi utilizado o script `descriptografar.py` para realizar o processo de recuperação dos arquivos.

Essa etapa demonstrou a importância do processo de descriptografia e permitiu verificar a restauração dos dados utilizados no experimento.

**Evidência 04 — Dados descriptografados**

![04 - Dados descriptografados](img/04%20-%20dados_descriptografados.png)

## ⚙️ Execução dos Scripts

Os scripts foram organizados de forma independente para demonstrar as duas etapas principais do experimento.

**Script de criptografia:**

```bash
python ransomware.py
```

Responsável pela simulação da criptografia dos arquivos de teste.

**Script de descriptografia:**

```bash
python descriptografar.py
```

Responsável pela recuperação dos arquivos utilizados na simulação.

**Observação:** a execução deve ocorrer conforme as instruções do arquivo `LEIA ISSO.txt`, respeitando a organização dos diretórios e os requisitos definidos no laboratório.

## 🔍 Análise Técnica

O desenvolvimento do laboratório permitiu compreender três componentes importantes de uma simulação de Ransomware.

### 1. Criptografia

É o processo de transformar informações legíveis em dados que não podem ser interpretados sem o mecanismo adequado de recuperação.

Em ataques reais, esse processo pode impedir que usuários acessem seus próprios arquivos.

### 2. Descriptografia

É o processo inverso da criptografia, utilizado para recuperar o conteúdo original dos arquivos por meio da chave correspondente.

No laboratório, essa funcionalidade foi implementada no script `descriptografar.py`.

### 3. Mensagem de Resgate

É uma mensagem apresentada por operadores de Ransomware para informar que os arquivos foram comprometidos e exigir pagamento para supostamente permitir sua recuperação.

No projeto, essa mensagem foi utilizada exclusivamente para fins demonstrativos e educacionais.

## 🛡️ Segurança da Informação — Prevenção contra Ransomware

O estudo também permitiu refletir sobre medidas importantes para reduzir os riscos associados a ataques de Ransomware.

Entre as principais estratégias de prevenção estão:

- **Backups periódicos:** manter cópias de segurança atualizadas e isoladas dos sistemas principais.
- **Atualizações de segurança:** manter sistemas operacionais e aplicações atualizados.
- **Antivírus e EDR:** utilizar ferramentas de proteção e monitoramento de ameaças.
- **Controle de acesso:** aplicar o princípio do menor privilégio.
- **Autenticação multifator (MFA):** adicionar uma camada extra de proteção às contas.
- **Conscientização dos usuários:** orientar sobre phishing, anexos suspeitos e links maliciosos.
- **Monitoramento:** identificar atividades incomuns e possíveis comportamentos maliciosos.
- **Plano de resposta a incidentes:** estabelecer procedimentos para contenção, investigação e recuperação.

## 📖 Conhecimentos Adquiridos

A realização deste laboratório contribuiu para o desenvolvimento dos seguintes conhecimentos:

- Fundamentos de Cibersegurança.
- Conceitos e classificação de malwares.
- Funcionamento de ataques de Ransomware.
- Programação Python aplicada à segurança.
- Conceitos de criptografia e descriptografia.
- Análise de arquivos em ambiente controlado.
- Identificação de riscos e vulnerabilidades.
- Estratégias de prevenção e recuperação de dados.
- Documentação técnica com Markdown.
- Versionamento e organização de projetos com Git e GitHub.

## 🎓 Formação e Referências

**Instituição de ensino:** DIO — Digital Innovation One.

**BootCamp:** Santander — Cibersegurança do Zero à Prática.

**Plataforma de aprendizagem:** [DIO — Digital Innovation One](https://www.dio.me/).

O projeto foi desenvolvido como atividade prática de aprendizagem dentro do BootCamp, com foco na aplicação dos fundamentos de Cibersegurança e programação Python.

## ⚠️ Aviso de Uso Educacional

Este projeto possui finalidade exclusivamente educacional e demonstrativa.

A simulação foi desenvolvida para compreender conceitos relacionados ao funcionamento de Ransomware em ambiente controlado, utilizando arquivos de teste próprios.

Os scripts não devem ser utilizados em arquivos de terceiros ou sistemas sem autorização. Experimentos de segurança devem respeitar os princípios éticos e legais.

## 🏁 Conclusão

A conclusão deste laboratório proporcionou uma experiência prática sobre o funcionamento de um dos tipos de malware mais relevantes no cenário atual da Cibersegurança.

Por meio da linguagem Python, foi possível compreender os conceitos de criptografia, descriptografia, indisponibilidade de dados e simulação de uma mensagem de resgate.

A implementação dos scripts `ransomware.py` e `descriptografar.py`, juntamente com a utilização dos arquivos de teste, permitiu acompanhar as diferentes etapas do experimento.

Além do desenvolvimento técnico, o projeto reforçou a importância de estratégias preventivas, como backups, controle de acesso, atualização de sistemas e conscientização dos usuários.

Este laboratório representa mais uma etapa da minha jornada de aprendizado em Cibersegurança, Python e Computação em Nuvem, fortalecendo meus conhecimentos por meio de atividades práticas e documentação técnica.

---

**Projeto desenvolvido durante o BootCamp Santander — Cibersegurança do Zero à Prática | DIO.**

Repositório destinado ao registro de estudos, experimentos e evolução profissional na área de Tecnologia da Informação e Cibersegurança.
