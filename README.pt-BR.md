<div align="center">

# Awesome Kling 4.0 Prompts — Guia em português

52 prompts originais e prontos para produção em cinema, publicidade, UGC, diálogo, VFX, animação, gastronomia, viagem, educação e redes sociais.

[English](README.md) · [Español](README.es-ES.md) · **Português (Brasil)** · [15 idiomas](docs/LANGUAGES.md)

[Catálogo](prompts/README.md) · [Método completo](docs/PROMPT-GUIDE.md) · [Áudio multilíngue](docs/MULTILINGUAL-AUDIO.md) · [FLAQ.AI](docs/FLAQ-AI.md)

</div>

> **Status do modelo — 29/09/2026:** Kling 4.0 Flash entrou em acesso antecipado em 28 de setembro para assinantes do plano Ultra anual. Segundo o [anúncio oficial da Kling AI](https://sg.linkedin.com/company/kling-ai-api), o Kling 4.0 completo e o acesso à API estão previstos para outubro de 2026, sem data exata. A geração nativa de até **30 segundos** foi anunciada para o modelo completo; esse limite ainda não está confirmado para o Flash. Os prompts atuais têm 5–15 segundos.

## Kling 4.0: novidades e disponibilidade

Segundo o [anúncio oficial da Kling AI no X](https://x.com/Kling_ai/status/2104596718067257458), o Flash está em acesso antecipado para assinantes Ultra anuais; o 4.0 completo e a API estão previstos para outubro de 2026. Para o modelo completo foram anunciados até 30 segundos por geração, 10 quadros-chave, 15 referências multimodais, saída de até 4K/10-bit HDR, áudio estéreo e mais idiomas e sotaques. **Esses números não são limites confirmados do Flash.** Os 52 prompts atuais usam cronogramas de 5–15 segundos. As páginas 4.0 da FLAQ.AI de [texto para vídeo](https://flaq.ai/models/kuaishou/kling-4-0-text-to-video/) e [imagem para vídeo](https://flaq.ai/models/kuaishou/kling-4-0-image-to-video/) ainda dizem “Coming Soon”; não são uma API 4.0 ativa.

## Vídeos e prompts no X

**Verificado em 29/09/2026.** O [vídeo oficial de apresentação](https://x.com/Kling_ai/status/2104596718067257458) é uma montagem da família 4.0; sua duração total não comprova a duração de uma geração Flash. Os casos abaixo são testes descritos pelos próprios criadores, não benchmarks oficiais nem reproduções independentes deste projeto. Consulte vídeos e textos integrais nos posts originais; não os copiamos.

| Post original | Ideia prática para testar |
|---|---|
| [Umesh: perseguição noturna de um gato, 20 s](https://x.com/umesh_ai/status/2104595267794460949) · [prompt original](https://x.com/umesh_ai/status/2104595270671724936) | Um protagonista, trajeto conectado e um evento físico por local; câmera acompanha sem cortes. |
| [OscarAI: show em anime, 20 s, com prompt](https://x.com/Artedeingenio/status/2104829034299351079) | O criador prefere instruções curtas e diretas nos testes iniciais, mas relata aderência imperfeita. Comece por sujeito → mudança → câmera → final. |
| [とすくん: mudança de clima, 15 s](https://x.com/tokyo_Valentine/status/2104810060811833710) · [prompt original](https://x.com/tokyo_Valentine/status/2104810064750239987) | Use a ficha da personagem só para identidade e roupa; marque separadamente quando clima, luz e atuação mudam. |
| [Alexandra Dekimpe: testes de produção](https://x.com/HadesDesign/status/2104878440889417957) | Descreva microações visíveis em vez de emoções abstratas; fixe causa e efeito com “somente depois”; dê fala exata ou peça silêncio. São observações da autora. |
| [Aswin Aji Raj: UGC em hindi, 20 s](https://x.com/Aswin_Aji_Raj/status/2104867308514779222) | O prompt completo não foi publicado. Defina falante e texto exato; revise pronúncia, sincronia labial e alegações do produto. |
| [@plasm0: comparação 3.0/Flash com mesmo prompt](https://x.com/plasm0/status/2104597949485629557) | Mantenha prompt e referências iguais para um teste A/B e registre as configurações. Um par de vídeos não é benchmark formal. |

**Exercício vertical original de 15 s, ainda não testado** (fora dos 52 prompts do catálogo; sem copiar textos do X):

~~~text
[OBJETO/REFERÊNCIA] Uma única lanterna recarregável de bicicleta, sem marca, com corpo grafite fosco e apenas um botão âmbar. Se houver imagem, ela fixa somente o formato da lanterna.
[CENA/CÂMERA] Oficina de bicicletas tranquila ao entardecer. Plano próximo e contínuo das mãos da mecânica até a lanterna e o guidão. Luz natural da janela; sem cortes ou teletransporte.
[0–4 s] Ela coloca a lanterna apagada ao lado do guidão; mostrar as duas mãos e o suporte.
[4–8 s] Encaixa a lanterna. Só depois do clique que confirma a fixação o polegar aperta o botão âmbar.
[8–12 s] A luz acende apenas uma vez, iluminando a roda dianteira e um pequeno trecho do chão. A câmera desliza de lado para revelar o feixe.
[12–15 s] Ela solta o guidão; a lanterna permanece firme. Sustentar um quadro final estável.
[ÁUDIO/RESTRIÇÕES] Som ambiente da oficina, um clique do encaixe e um do botão; sem fala ou música. Preservar formato, número de mãos, posição e direção da luz. Sem marca, lanternas extras ou cortes sem motivo.
~~~

Teste tanto instruções breves quanto roteiros longos, mas bem estruturados. Registre modo, duração, referências e resultado antes de marcar uma receita como “testada”. Contribuições originais são bem-vindas pelo [guia de contribuição](CONTRIBUTING.md).

## Estrutura rápida

```text
[SAÍDA] duração, proporção, tomada única/múltiplos planos, acabamento
[CONTINUIDADE] características fixas de pessoa, roupa, produto e objetos
[ESPAÇO] local, horário, luz e posições iniciais
[PLANOS POR TEMPO] uma ação principal + uma intenção de câmera por trecho
[ATUAÇÃO E FÍSICA] olhar, respiração, contato, peso e inércia
[ÁUDIO] falante, idioma, tom, ambiente, foley e música
[RESTRIÇÕES] identidade, direção, luz, texto, logotipos e deformações
```

Português é um idioma de documentação deste projeto, mas não está na lista verificada de fala nativa do Kling 3.0. Teste a fala no modelo ativo ou adicione uma locução revisada na pós-produção.

## Destaques

- [Reencontro multilíngue](prompts/cinematic-and-dialogue.md#2-the-paper-crane-at-platform-seven)
- [Anúncio de bebida botânica](prompts/commercial-and-ugc.md#1-botanical-spark-product-reveal)
- [Perseguição de ficção científica](prompts/action-and-vfx.md#1-the-glass-manta-pursuit)
- [Loop cômico do guarda-chuva](prompts/education-documentary-social.md#3-the-infinite-umbrella-problem)

## Sobre a FLAQ.AI

> Em 29/09/2026, as páginas FLAQ.AI 4.0 de [texto para vídeo](https://flaq.ai/models/kuaishou/kling-4-0-text-to-video/) e [imagem para vídeo](https://flaq.ai/models/kuaishou/kling-4-0-image-to-video/) exibem “Coming Soon”. O acesso antecipado ao Flash na Kling não significa que a API 4.0 da FLAQ.AI esteja disponível.

[FLAQ.AI](https://flaq.ai/) é uma plataforma web e uma camada de API unificada para modelos de imagem, vídeo e linguagem. Atualmente oferece páginas para [Kling 3.0 Standard Text-to-Video](https://flaq.ai/models/kuaishou/kling-3-0-std-text-to-video/) e [Image-to-Video](https://flaq.ai/models/kuaishou/kling-3-0-std-image-to-video/). Este projeto não afirma que Kling 4.0 esteja disponível. Confira controles, preços e documentação ao vivo antes da produção.
