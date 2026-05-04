# 🏥 ClinApp — Gestão de Agenda Clínica

Sistema de gestão de agenda para **psicólogos** e **nutricionistas**, 100% frontend em HTML/CSS/JS puro. Zero dependências, zero build tools.

![ClinApp Preview](https://clinappsaas.netlify.app/)

## ✨ Funcionalidades

| Módulo | O que faz |
|---|---|
| **Dashboard** | Visão geral do dia: consultas, métricas e lembretes pendentes |
| **Agenda** | Grade semanal com visualização por horário e cadastro de consultas |
| **Pacientes** | Cadastro, busca e gestão de pacientes (psicologia e nutrição) |
| **Prontuário** | Histórico clínico por paciente com anotações de sessão |

## 🚀 Como rodar

Não precisa instalar nada. Basta abrir o arquivo:

```bash
# Opção 1 — abrir direto no navegador
open index.html

# Opção 2 — rodar um servidor local simples
npx serve .
# ou
python3 -m http.server 3000
```

## 📁 Estrutura

```
clinapp/
├── index.html       # App completo (HTML + CSS + JS)
├── README.md
└── docs/
    └── preview.png  # Screenshot do app
```

## 🛠️ Stack

- HTML5 semântico
- CSS3 com variáveis (dark mode automático)
- JavaScript vanilla (sem frameworks)
- Zero dependências externas

## 🗺️ Roadmap

- [ ] Persistência com `localStorage` / backend
- [ ] Integração WhatsApp para lembretes automáticos
- [ ] Exportação de prontuário em PDF
- [ ] Controle de pagamentos / faturamento
- [ ] Autenticação multi-profissional
- [ ] Versão mobile (PWA)
- [ ] Integração com Google Calendar

## 🤝 Contribuindo

Pull requests são bem-vindos! Para mudanças grandes, abra uma issue primeiro para discutirmos o que você gostaria de mudar.

1. Fork o projeto
2. Crie sua branch (`git checkout -b feature/nova-funcionalidade`)
3. Commit suas mudanças (`git commit -m 'feat: adiciona X'`)
4. Push para a branch (`git push origin feature/nova-funcionalidade`)
5. Abra um Pull Request

## 📄 Licença

MIT — veja o arquivo [LICENSE](LICENSE) para detalhes.

---

Feito com ☕ para profissionais de saúde brasileiros.
