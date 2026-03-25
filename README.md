# 🏥 AMU Digital

Repositório de formulários médicos digitais interativos da **MedMais Group**, desenvolvidos para uso no ambiente de Atendimento Médico de Urgência (AMU).

Cada formulário é uma página HTML autossuficiente, totalmente editável no navegador, com botões de **Salvar em PDF** e **Imprimir**.

---

## 📁 Estrutura do Repositório

```
AMU-Digital/
├── formulario-atendimento-basico-FOR054/
│   └── index.html          # Formulário de Atendimento Básico
│
├── ficha-pre-hospitalar-rodoviario-FOR013/
│   └── index.html          # Ficha de Atendimento Pré-Hospitalar Rodoviário
│
└── README.md
```

---

## 📋 Formulários Disponíveis

### 1. Formulário de Atendimento Básico
**Código:** `MMS.BR.EF.FOR.054` | **Revisão:** 00

Utilizado para registro de atendimentos clínicos em ambiente aeroportuário. Inclui:
- Identificação do paciente
- Histórico atual / queixas
- Sinais vitais
- Escala Visual Analógica (EVA) interativa
- Avaliação rápida XABCDE
- Anotação de enfermagem
- Desfecho do paciente
- Termo de recusa de atendimento
- Insumos utilizados

---

### 2. Ficha de Atendimento Pré-Hospitalar Rodoviário
**Código:** `MMS.BR.RV.FOR.013`

Utilizada por equipes de resgate em ocorrências rodoviárias. Inclui:
- Identificação do paciente e veículo
- Gravidade e triagem START
- Avaliação primária XABCDE
- Lesões aparentes com diagrama corporal
- Avaliação secundária (SAMPLE + sinais vitais)
- Tipo de acidente e mecanismo de trauma
- Escala de Coma de Glasgow (interativa)
- Veículos envolvidos e salvamento veicular
- Exame da cabeça aos pés
- Evolução clínica
- Materiais utilizados
- Equipe e recusa de atendimento

---

## 🚀 Como Usar

1. Faça o download ou clone o repositório:
   ```bash
   git clone https://github.com/SEU_USUARIO/AMU-Digital.git
   ```

2. Abra o arquivo `index.html` da pasta desejada diretamente no navegador (Chrome, Edge ou Firefox recomendados).

3. Preencha os campos normalmente.

4. Use os botões no topo da página:
   - **⬇️ Salvar em PDF** — gera um PDF com todos os dados preenchidos
   - **🖨️ Imprimir** — abre o diálogo de impressão sem a barra de botões

> ⚠️ Nenhum dado é enviado para servidores. Tudo funciona localmente no navegador.

---

## 🛠️ Tecnologias

- HTML5 + CSS3 puro
- JavaScript vanilla
- [html2pdf.js](https://github.com/eKoopmans/html2pdf.js) para geração de PDF

---

## 📌 Roadmap

- [ ] Versão mobile responsiva
- [ ] Salvamento local (localStorage) para rascunhos
- [ ] Exportação para Excel / banco de dados
- [ ] Autenticação e histórico de atendimentos
- [ ] Integração com sistemas hospitalares (HL7/FHIR)

---

## 🤝 Contribuições

Pull requests são bem-vindos! Para mudanças maiores, abra uma issue primeiro para discutir o que você gostaria de alterar.

---

*MedMais Group — Tecnologia a serviço da saúde*
