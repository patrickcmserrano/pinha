# Pinha

Site institucional da **Pinha** — a plataforma privada de IA.

**Marcas e camadas:** **Ping Hai** (平海) é a **empresa** — a entidade comercial,
quem assina a entrega e recebe o contato. **Pinha** é o **produto** — a plataforma
privada de IA que este site vende. **AI Factory** é o motor que a plataforma roda
por dentro, e não é a marca pública. Ver `COERENCIA.md` no monorepo de trabalho
(`~/dev/pinha/docs/COERENCIA.md`).

Página única, estática: HTML + CSS + um script de tema. Sem framework, sem build,
sem dependências, sem backend, sem cookies, sem requisição externa (só a fonte
do Google Fonts).

## O que a página afirma

- **A entrega real:** uma plataforma privada de IA em produção para um cliente
  (um centro de tecnologia e inovação), com SSO federado, RAG governado, frota de
  inferência própria e auditoria sem acesso a conteúdo.
- **O que NÃO afirma:** nome de cliente em peça pública, adoção comercial
  (é **um** cliente), benchmark publicado, SLA, "líder", "estado da arte".
  Nenhum nome interno de componente aparece.

## A ideia da marca

A **pinha** é o fruto da araucária: uma estrutura fechada que protege a semente do
frio e a libera só na hora certa. É a metáfora do produto — o conhecimento da
empresa fica guardado, e é liberado quando e para quem deve ser liberado.

> *"Em IA corporativa, privacidade não é uma promessa de termos de uso; é o desenho
> físico e lógico do sistema."*

## Verificar localmente

```sh
xdg-open index.html
# ou
python3 -m http.server 8899
```

## Publicar (GitHub Pages)

O site é servido pela branch `main`, na raiz do repositório, com Pages já ativado
(`source: main /`, HTTPS forçado).

URL: **https://patrickcmserrano.github.io/pinha/**

## Licença

Conteúdo e código são proprietários. Todos os direitos reservados.
