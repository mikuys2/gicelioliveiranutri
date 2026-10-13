# Giceli Oliveira: prévia `index-v2.html`, fontes e pendências

Documento interno (não aparece para o visitante). Levantamento feito em 11/10/2026.
A prévia `index.html` (versão anterior) não foi alterada.

## Fontes consultadas

| Fonte | O que foi usado |
| --- | --- |
| gicelioliveiranutr.wixsite.com/emagrecimento (home) | Texto "Sobre mim", missão, visão, valores, formação UFBA, UNEB, "pizza do domingo", frase "Não é sobre o peso...", "Vem comigo..." |
| /vendas (Programa de Emagrecimento) | Público (mulheres, de 5 kg a 50 kg ou mais), reeducação sem proibições, etapas da primeira consulta, o que o paciente recebe, 3 dicas contra efeito sanfona, "valores, planos e horários pelo WhatsApp ou telefone" |
| /services e /service-page/emagrecimento-2 | Nomes e durações dos 7 serviços, "Consulte valores", descrição do Emagrecimento, unidades Ícone Tower e CEO Salvador Shopping |
| /voce-pergunta-e-eu-respondo (respostas em pop-up) | Perguntas e respostas com o nome de quem perguntou |
| /noticias (Na Mídia) | Prêmio Top of Mind, Nutri na mídia, Doctoralia, COVID-19, Rancho Catarinense, câncer de mama (BATV), Rádio Sociedade, Outubro Rosa, ensaio LF Fotografia |
| /contatos | Endereço antigo e telefones (71) e (75) |
| whats.link/nutrigicelioliveira (botão WhatsApp do site) | Redireciona para +55 71 98673-1801 |
| Google Maps, ficha de Feira de Santana | 5,0 com 123 avaliações, endereço, telefone (75) 99169-7851, textos das avaliações |
| Google Maps, ficha de Salvador | 5,0 com 26 avaliações, endereço, telefone (75) 99169-7851, avaliação de Stefany F. |
| instagram.com/nutrigicelioliveira | Perfil existe ("Giceli Oliveira, Nutricionista") |
| Logo (img/logo-full.png) | CRN5 8265 |
| Imagens (img/) | Fotos originais do site Wix, já otimizadas na pasta |

## Divergências encontradas (precisam de confirmação da cliente)

1. **Endereço de Feira de Santana.** A página Contatos diz "Av. Getúlio Vargas, 854, Edf. Medical Service, Sala 206". O Google e a página do serviço no Wix dizem "Av. Getúlio Vargas, 792, Edf. Ícone Tower, Sala 607". A prévia usa o Ícone Tower (duas fontes concordam). Confirmar e corrigir a página Contatos no site atual.
2. **Horários.** O FAQ do site diz "terças, quartas e quintas, das 08 às 18h". O Google diz "Aberto 24 horas" (Feira) e "abre às 07:00" (Salvador). A prévia **não mostra horário fixo**: diz "atendimento com hora marcada, consulte os horários pelo WhatsApp". Por isso a pergunta da Cassia de Assis sobre horários ficou fora do FAQ.
3. **Prazo da dieta.** O site diz que a dieta é entregue "após 8 dias". Avaliações recentes no Google dizem que a paciente saiu "com minha dieta em mãos" e que o plano foi "construído com paciente no mesmo momento". A prévia não cita prazo. Confirmar qual vale hoje.
4. **Tempo de experiência.** A home diz "experiência de 5 anos na área clínica", texto sem data. Não usado.

## Contato e links

- Todos os botões de agendamento abrem `https://wa.me/5571986731801` com mensagem contextual (uma por serviço). É o único número confirmado como WhatsApp.
- (75) 99169-7851 aparece como **telefone** (`tel:`), porque é o número do botão "Telefone" do site e das duas fichas do Google. **Pendência:** confirmar se esse número também atende por WhatsApp.
- Não foi feita associação de número a unidade: as duas fichas do Google usam o mesmo (75).
- "Abrir no mapa": Feira usa a ficha do Google (`?cid=8100686036887856959`); Salvador usa uma busca pelo nome da ficha. Pendência: obter o link direto da ficha de Salvador.
- Redes: Instagram @nutrigicelioliveira e Facebook /nutrigicelioliveira (este vem do site atual).

## Avaliações

- Fonte: Google Maps, conferidas palavra por palavra em 11/10/2026. Publicadas com primeiro nome e inicial.
- Selecionadas 8 de 149. A página diz que é uma seleção e identifica os trechos.
- Evitei depoimentos que citam perda de peso em quilos ou prazos de resultado, por cautela com o Código de Ética do Nutricionista (Res. CFN 599/2018). **Confirmar com a cliente** se ela usa depoimentos no material dela e em que formato.
- Trechos (texto completo no Google): Iumara S., Edna S., Gabrielle A., Denise N., Stefany F.
- Completos: Juyara G., Monielly M., Lauréviz.

## O que não foi incluído por falta de confirmação

- Seção de planos (sessão pontual, 90 dias, 180 dias). O site cita "planos", mas não diz nomes, duração, frequência nem itens. Nada foi criado.
- Preços. O site diz apenas "Consulte valores".
- Descrições de Saúde da Mulher, Esteatose Hepática, Doenças Metabólicas, Nutrição e Saúde Gastrointestinal e Testes Nutrigenéticos: o site não tem texto para esses serviços. Exibidos só com nome e duração. **Pedir 1 ou 2 frases de cada à cliente.**
- Atendimento online: não mencionado em nenhuma fonte.

## Pendências técnicas antes de publicar

- Fontes (Playfair Display e Figtree) carregam do Google Fonts na prévia. Para produção, hospedar os arquivos localmente.
- As fotos dos serviços (exceto Emagrecimento e Bioimpedância) parecem ser de banco de imagens vindas do Wix. Confirmar se a cliente tem licença ou prefere fotos próprias.
- Mapa de URLs para redirecionamento, caso o domínio passe a apontar para a nova página:
  - `/about-5` → `#sobre`
  - `/vendas` → `#emagrecimento`
  - `/services` e `/service-page/emagrecimento-2` → `#servicos` / `#emagrecimento`
  - `/noticias` → `#midia`
  - `/voce-pergunta-e-eu-respondo` → `#duvidas`
  - `/contatos` → `#unidades`
  - `/conteudo-gratuito` → não analisada (sem conteúdo identificado); definir destino.
- O formulário "Deixe aqui a sua pergunta" do site atual não foi reproduzido; o botão "Enviar uma dúvida" leva ao WhatsApp.
