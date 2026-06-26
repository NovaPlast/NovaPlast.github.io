# Ficha Cadastral – Novaplast

Formulário web de cadastro de clientes da Novaplast, hospedado via GitHub Pages.

## Acesso

O formulário está disponível em:
**https://novaplast.github.io/**

## Funcionalidades

- Cadastro para três tipos de cliente: Pessoa Física, Pessoa Jurídica e Produtor Rural
- Campos condicionais — cada tipo exibe apenas os campos necessários
- Validação matemática de CPF e CNPJ
- Máscaras de formatação para CPF, CNPJ, telefone e CEP
- Preenchimento automático de endereço por CEP (API ViaCEP)
- Validação de todos os campos obrigatórios antes de avançar
- Envio automático por e-mail para a equipe de faturamento via Formspree
- Instruções para envio de documentos por e-mail

## Arquivos

| Arquivo | Descrição |
|---|---|
| `index.html` | Formulário completo (HTML + CSS + JavaScript) |
| `logo_novaplast.png` | Logo da Novaplast (branca com fundo transparente) |
| `DOCUMENTACAO.md` | Documentação técnica para manutenção e alterações |
| `GUIA_FATURAMENTO.md` | Guia de uso para a equipe de faturamento |
| `README.md` | Este arquivo |

## Documentação

Para alterar campos, cores, e-mails ou configurações do Formspree, consulte o arquivo `DOCUMENTACAO.md`.

Para dúvidas sobre como receber e interpretar os cadastros, a equipe de faturamento pode consultar o `GUIA_FATURAMENTO.md`.

## Tecnologias utilizadas

- HTML, CSS e JavaScript puro (sem frameworks)
- [Formspree](https://formspree.io) para envio de e-mail
- [ViaCEP](https://viacep.com.br) para preenchimento automático de endereço
- GitHub Pages para hospedagem
