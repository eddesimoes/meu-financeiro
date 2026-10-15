MEU FINANCEIRO 2.0 — PWA Android

CONTEÚDO
- index.html: app financeira
- manifest.json: metadados para instalação
- sw.js: cache offline (service worker)
- icons/: ícones da aplicação

TESTAR
1. Extraia o ZIP.
2. Para instalar como PWA, publique a pasta num host HTTPS (por exemplo, GitHub Pages gratuito) ou teste em localhost.
3. No Android, abra o endereço no Chrome > menu ⋮ > Instalar app / Adicionar ao ecrã principal.
4. Dados ficam no armazenamento local do navegador; exporte backups.

IMPORTANTE SOBRE OPEN BANKING
A ligação automática ao Revolut NÃO está implementada. O acesso de produção da API Open Banking do Revolut destina-se a prestadores terceiros regulados e exige os requisitos de autorização/certificados aplicáveis. A Tink oferece sandbox com dados de teste, mas o acesso de produção tem condições comerciais. Esta app tem importação CSV manual e não pede credenciais bancárias.

SEGURANÇA / LIMITAÇÕES
- Não é um serviço bancário nem aconselhamento financeiro.
- Não armazena dados num servidor nem sincroniza dispositivos.
- Proteja o dispositivo e exporte backups.
- Antes de utilizar com dados reais, teste importação, exportação e restauração.
