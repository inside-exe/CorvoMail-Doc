# Como contribuir

Contribuições de interface, acessibilidade, documentação, correções e compatibilidade com a API são bem-vindas.

## Antes de começar

- Verifique issues existentes.
- Não publique tokens, chaves de caixas ou mensagens reais.
- Mantenha a interface e a documentação em português.
- Preserve os avisos sobre retenção e privacidade.

## Fluxo sugerido

1. Faça um fork do repositório.
2. Crie uma branch descritiva.
3. Instale dependências com `pnpm install`.
4. Faça alterações pequenas e focadas.
5. Execute `pnpm lint` e `pnpm build`.
6. Abra um pull request explicando o problema e a solução.

## Padrões básicos

- TypeScript sem erros.
- Componentes acessíveis e responsivos.
- Sem `localStorage` adicional para dados que deveriam ficar no servidor.
- Sem inclusão de rastreadores ou coleta de dados sem discussão prévia.
- Sem promessas de anonimato, retenção ou entrega garantida.

## Documentação

Ao mudar comportamento visível, atualize os arquivos correspondentes em `docs/`. Links devem continuar funcionando quando a pasta for copiada para a raiz do repositório `inside-exe/CorvoMail-Doc`.
