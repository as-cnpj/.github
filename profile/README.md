## AS-CNPJ

Ecossistema autoral de bibliotecas para validação, normalização e formatação de CNPJ numérico e alfanumérico.

A Receita Federal anunciou que a partir de **julho de 2026** o CNPJ passará a aceitar letras nas 12 primeiras posições. Isso impacta bancos de dados, APIs, ERPs, schemas, formulários e integrações. O AS-CNPJ resolve isso com bibliotecas **corretas, auditáveis e consistentes entre linguagens**.

### Princípios

- Implementação própria — sem copiar código de terceiros
- Base oficial da Receita Federal
- Mesmo comportamento funcional entre linguagens
- Vetores de teste compartilhados como contrato
- API pequena e auditável
- Zero dependências no núcleo

### Repositórios

| Repo | Descrição | Status |
| --- | --- | --- |
| [as-cnpj](https://github.com/as-cnpj/as-cnpj) | Hub central — manifesto, especificação, vetores de teste e governança | Ativo |
| [as-cnpj-js](https://github.com/as-cnpj/as-cnpj-js) | Biblioteca autoral para JavaScript e TypeScript | Publicado |
| [as-cnpj-python](https://github.com/as-cnpj/as-cnpj-python) | Biblioteca autoral para Python | Implementado |

### Instalação rápida

```bash
npm install @ascnpj/core
```

```python
pip install ascnpj
```

### Links

- 🌐 [as-cnpj.org](https://as-cnpj.org) — Site e documentação
- 📖 [Documentação](https://as-cnpj.org/pt/docs) — API, regras, vetores, especificação
- 📋 [Auditoria de segurança](https://as-cnpj.org/pt/docs?page=audit)
- 🛡️ [Política de segurança](https://as-cnpj.org/pt/docs?page=security-policy)
- 🤝 [Como contribuir](https://as-cnpj.org/pt/docs?page=contributing)
- 💬 [Comunidade](https://as-cnpj.org/pt/community) — Apoiadores e implementações
- 🗣️ [Discussions](https://github.com/as-cnpj/as-cnpj/discussions) — Enviar apoio ou depoimento

### Maintainer

[@0moura](https://github.com/0moura) · ascnpj@0moura.io
