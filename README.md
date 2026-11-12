# VendasHubii — Cliente

Aplicativo para Windows dos computadores da loja. Abre as telas do VendasHubii (pedidos, despacho, estoque, devoluções, financeiro)
e imprime etiquetas e listas direto nas impressoras do próprio PC.

Ele precisa do **servidor VendasHubii da loja**: sem o endereço e o login dele, o aplicativo não tem o que mostrar.

## Instalar

1. Abra a página de [Releases](../../releases) e, na versão **Cliente 1.x.y** mais recente, baixe `Instalador-VendasHubii-Cliente.exe`.
2. Execute o instalador. A instalação é por usuário e **não pede administrador**; ao terminar, o aplicativo abre sozinho.
3. Na primeira vez, informe o endereço do servidor da loja e entre com seu nome e PIN.

> **Aviso do Windows.** O instalador ainda não tem assinatura digital, então o Windows pode mostrar "O Windows protegeu o seu
> computador". Clique em **Mais informações → Executar assim mesmo**. Em PCs com o *Controle inteligente de aplicativos* ligado,
> o Windows pode bloquear a instalação: peça a quem administra o PC.

## Atualizações

O aplicativo se atualiza sozinho, como o VS Code. Você **não precisa baixar o instalador de novo**:

- a cada 30 minutos ele confere se há versão nova e baixa em segundo plano;
- quando termina, pergunta **Reiniciar agora** ou **Depois**; ao reiniciar, já abre na versão nova;
- sem internet, o aplicativo continua funcionando normalmente e tenta de novo depois.

### Versões

| Nome na release | Para quem | Atualiza para |
|---|---|---|
| **Cliente 1.x.y** | Os PCs da loja (versão liberada) | A próxima versão liberada |
| **Cliente beta** (pré-lançamento) | Só quem testa as novidades | O próximo beta |

Quem instala a versão liberada nunca recebe um beta, e quem instala o beta só recebe betas. Em caso de dúvida, use sempre a
**Cliente 1.x.y**.

## Requisitos

- Windows 10 ou 11, 64 bits;
- acesso de rede ao servidor da loja;
- as impressoras instaladas no próprio PC.

## Problemas comuns

- **O aviso de atualização não apareceu.** A conferência é a cada 30 minutos; feche e abra o aplicativo para ela rodar de novo.
- **Quero desinstalar.** *Configurações → Aplicativos → VendasHubii → Desinstalar*.
- **Não consigo entrar.** Confira o endereço do servidor e o PIN com quem administra o VendasHubii da loja.

## Sobre este repositório

Aqui ficam **apenas os instaladores e os pacotes de atualização**, publicados automaticamente a cada versão. O código-fonte do
VendasHubii não está neste repositório. Não registre aqui dados da loja, de clientes ou de pedidos.
