# Programa de Telehealth · Conceito Doctor Assist

**Protótipo navegável · Lilly Brazil · Medical Affairs CMH**

Conceito de programa de telehealth para doenças crônicas (obesidade + diabetes) com foco em retenção, engajamento e outcomes clínicos.

🔗 **Demo:** https://fmccode01.github.io/telehealth02/

---

## 🎯 O que está dentro

### Programa OBESIDADE · Mariana, 42a · tirzepatida
- Home com peso em tendência (não diário)
- Hub de tratamento · titulação · check-in pós-aplicação
- Rastreador GI · ruído alimentar (food noise)
- Mapa de Sentimento pré-consulta (SentimentMap)
- Hub de questionários (PHQ-9, GAD-7, TFEQ-R18, EAT-26 em linguagem do paciente)
- Padrão alimentar dinâmico · 4 fenótipos
- Comunidade Flag.gy · matching por similaridade clínica
- Voz nas redes (advocacy) com confirmação LGPD-aware
- Chat clínico com Dr. Lucas (WhatsApp)

### Programa DIABETES · Lúcia, 64a · DM2 há 12 anos
- Home com glicemia (CGM Libre) + PA (Omron) + peso + doses do dia
- Tela de glicemia 24h com Tempo no Alvo (TIR)
- Tela de pressão arterial com tendência semanal
- Tela de peso · cada kg melhora glicose · com curva 12 meses
- Chat WhatsApp clínico com Dr. Almeida (6 mensagens reais)
- Rastreio de complicações · 6 frentes em linguagem do paciente
- Saúde mental (PHQ-9, GAD-7, PAID-5) com explicação de propósito

### Visão do Médico (HCP)
- **Obesidade:** Painel da Mariana + análises macro da coorte
- **Diabetes:** Prontuário da Lúcia · 3 colunas (dados, hipóteses, medicações) + comparação com estudo SURMOUNT-1

### Cinco Decisões Estratégicas
1. Moeda do app é resposta ao tratamento · não peso/HbA1c
2. Doctor Assist vê o filme entre consultas
3. Cada paciente comparado à curva do estudo pivotal
4. Educação é produto, não FAQ
5. Comunidade com proteção clínica · não Reddit aberto

---

## 📁 Estrutura

| Arquivo | O que é |
|---|---|
| `prototype.html` | Protótipo navegável · ~1,5 MB · tudo embutido |
| `index.html` | Landing editorial com link pro protótipo |
| `README.md` | Este arquivo |

---

## 🧪 Como testar

1. Acesse https://fmccode01.github.io/telehealth02/
2. Click em "abrir protótipo"
3. No topo · alternar entre programas Obesidade ↔ Diabetes
4. Pills de fase abaixo · mudam contexto
5. Navegar pelas telas via bottom tabs, jump shortcuts ou mapa lateral

---

## 🔐 Confidencialidade

Conceito interno · Lilly Brazil. Personas fictícias inspiradas em casos clínicos típicos. Nenhum dado real foi usado.

---

**Versão:** v5 · maio 2026
**Stack:** HTML/CSS/JS puro · sem build · sem dependências externas (exceto Google Fonts)
