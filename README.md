# REURB MACHADINHO — Protótipo Android e PC

Este pacote contém uma aplicação web responsiva, preparada como PWA (Progressive Web App).

## Como testar no computador
Abra `public/index.html` em um navegador para visualizar a interface. Para testar instalação PWA e cache offline, publique em um serviço HTTPS (por exemplo, Render Static Site) ou execute um servidor local.

## Como instalar no Android
1. Publique o projeto em HTTPS.
2. Abra o endereço no Chrome do Android.
3. Use o menu do navegador e escolha **Instalar aplicativo** ou **Adicionar à tela inicial** (a opção varia conforme o navegador).
4. O ícone REURB será adicionado à tela inicial.

## Publicação no Render
- Crie um repositório GitHub novo e envie a pasta `public` e este `README.md`.
- No Render, crie um **Static Site** conectado ao repositório.
- Branch: `main`
- Build Command: deixe vazio
- Publish Directory: `public`

## Limitações importantes desta versão
- É um protótipo front-end. Os registros são armazenados no `localStorage` do navegador e não são sincronizados entre celulares e computadores.
- Não há servidor, banco PostgreSQL/PostGIS, login, perfis, assinatura, protocolo oficial ou transmissão para a Prefeitura.
- O mapa usa OpenStreetMap e um marcador aproximado. Não contém perímetro ou lotes oficiais.
- Não inserir CPF, RG, comprovantes, documentos pessoais ou dados reais nesta demonstração.
- Os dados locais podem ser apagados pelo navegador ou perdidos ao limpar seus dados.
- O pré-cadastro não comprova propriedade ou posse e não concede título.

## Próxima etapa de produção
Para uso oficial será necessário validar requisitos com a Prefeitura, definir base legal e política de privacidade (LGPD), implantar API segura, banco PostgreSQL/PostGIS, autenticação, autorização por perfil, armazenamento protegido de documentos, backups, auditoria e integração com a base geoespacial oficial.
