# Deploy e domínio

## Publicar na Vercel

1. Importe o repositório do aplicativo na Vercel.
2. Confirme a detecção do framework Next.js.
3. Use `pnpm build` como comando de build, caso não seja detectado automaticamente.
4. Publique o projeto.

A versão atual não depende de variáveis de ambiente.

## Configurar corvomail.online

1. Abra o projeto na Vercel.
2. Acesse **Settings > Domains**.
3. Adicione `corvomail.online`.
4. Adicione também `www.corvomail.online` se desejar.
5. No provedor do domínio, aplique os registros DNS exibidos pela Vercel.
6. Escolha o domínio canônico e configure o redirecionamento da outra versão.

A propagação DNS pode levar algum tempo. Verifique se HTTPS foi emitido antes de divulgar o endereço.

## Observação importante

Configurar `corvomail.online` aponta apenas o site. Isso não transforma o domínio em domínio de recebimento de e-mails. Os endereços temporários continuam usando domínios fornecidos pelo mail.tm.

## Validação pós-deploy

- Gere uma caixa.
- Copie o endereço.
- Envie uma mensagem de teste.
- Atualize e abra a mensagem.
- Salve as credenciais, gere outra caixa e recupere a anterior.
- Confira as seções Sobre, FAQ e o link da documentação.
