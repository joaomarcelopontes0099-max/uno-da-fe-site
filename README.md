# UNO da Fé — Landing Page

Site estático (HTML + CSS puro, sem build, sem dependências). Basta abrir `index.html` no navegador pra visualizar localmente, ou publicar como está.

## Estrutura

```
site/
├── index.html       ← página inteira (HTML + CSS inline)
├── assets/           ← todas as imagens reais usadas no site
└── README.md
```

## Como publicar (VS Code → GitHub → Vercel)

1. Abra esta pasta (`site`) no VS Code.
2. Vá na aba **Source Control** (ícone de ramificação na lateral esquerda) → botão **Publish to GitHub**. O VS Code cria o repositório e faz o login na sua conta — essa parte é feita direto por você, no seu VS Code.
3. Entre em [vercel.com](https://vercel.com) → **Add New → Project → Import** e selecione o repositório que acabou de criar.
4. A Vercel detecta que é um site estático (sem framework, sem build command) e publica direto. Não precisa configurar nada.
5. Pronto: a partir daí, qualquer commit + push nesse repositório (feito por você no VS Code, ou por mim nos mesmos arquivos) atualiza o site no ar automaticamente.

## Pendências antes de divulgar de verdade

Essas ficaram marcadas nas conversas anteriores e ainda precisam da sua decisão:

- **Link de checkout**: os botões de CTA (`#comprar`, `href="#"`) ainda não apontam pra nenhuma plataforma de pagamento real. Trocar assim que escolher Hotmart/Kiwify/Eduzz etc.
- **Texto de garantia**: está com o texto genérico de 7 dias. Vale confirmar se bate com a política real da plataforma de checkout escolhida.
- **Depoimentos**: a seção está com placeholder honesto ("estamos colhendo os primeiros relatos"), sem nomes ou citações inventadas. Trocar por depoimentos reais assim que tiver.
- **E-mail de contato no rodapé**: está como `contato@unodafe.com.br` (placeholder) — trocar pelo seu e-mail de suporte real.
- **Marca UNO**: por decisão sua, os criativos mantêm o nome e visual "UNO da Fé" seguindo a identidade original do produto. Vale ficar de olho em eventual notificação da Mattel (dona da marca UNO) se o tráfego pago escalar.

## Onde tudo mora

- Copy e estrutura completa da página: decidido e documentado em `estrutura-landing-page-uno-da-fe.md`, na pasta principal de outputs (fora desta pasta `site`).
- Imagens em `assets/`: cartas reais do baralho (extraídas do material original), fotos de estilo de vida geradas por IA (família, mãos jogando, turma de escola dominical) e miniaturas dos outros 18 jogos do "Baú de Jogos da Fé".
