# Python — materiais e notebooks didáticos

Repositório de materiais de estudo e apoio a aulas de programação em Python, bancos de dados e desenvolvimento de aplicações.

> **Nota de autoria e uso:** os materiais estão associados a atividades de formação. A publicação neste repositório não significa que todos os exemplos, apostilas ou recursos de terceiros sejam de autoria exclusiva do mantenedor ou estejam licenciados para redistribuição. Confirme a origem e as permissões de cada material antes de copiar, adaptar ou reutilizar comercialmente.

## Conteúdo

| Pasta | Descrição |
| --- | --- |
| [notebooks](notebooks/) | Apostilas e exercícios em Jupyter Notebook; parte do conteúdo é acompanhada por arquivos de dados |
| [codigos-fonte](codigos-fonte/) | Exemplos de programação |
| [database](database/) | Arquivos locais de banco de dados para exercícios |
| [assets](assets/) | Imagens e materiais auxiliares |

## Execução

```bash
python -m venv .venv
# Windows: .venv\\Scripts\\activate
# Linux/macOS: source .venv/bin/activate
python -m pip install -r requirements.txt
jupyter notebook
```

**Atenção:** o arquivo `requirements.txt` reflete dependências de materiais variados; instalar tudo pode exigir ajustes de versão e ambiente. Prefira ambientes isolados e revise os requisitos de cada notebook.

## Engenharia e manutenção

- Material de apoio didático; não é biblioteca preparada para produção.
- Notebooks podem depender de dados locais e versões específicas.
- Revise licenças, créditos, dados pessoais e permissões de publicação antes de redistribuir conteúdos de terceiros.

**Contato:** [Denis Correia](https://github.com/Deniscs873) · [LinkedIn](https://www.linkedin.com/in/denis-correia/)
