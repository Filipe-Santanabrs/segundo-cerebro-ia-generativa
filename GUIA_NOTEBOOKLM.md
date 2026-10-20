# Guia de execução no Gemini Notebook

## 1. Criar o notebook

1. Acesse [Gemini Notebook](https://notebook.google.com/).
2. Entre com sua conta Google.
3. Crie um notebook vazio.
4. Use o nome: `IA generativa no desenvolvimento de software`.

## 2. Adicionar as quatro fontes

Adicione cada endereço separadamente:

1. Artigo do Google:
   `https://developers.google.com/machine-learning/intro-to-ml/what-is-ml`
2. Vídeo do YouTube:
   `https://www.youtube.com/watch?v=S2GqQ4gJAH0`
3. Pesquisa do GitHub:
   `https://github.blog/news-insights/research/research-how-github-copilot-helps-improve-developer-productivity/`
4. PDF do NIST:
   `https://doi.org/10.6028/NIST.AI.600-1`

Se o link DOI do NIST não for importado, baixe o PDF pela página oficial e envie o arquivo manualmente:

`https://www.nist.gov/publications/artificial-intelligence-risk-management-framework-generative-artificial-intelligence`

Confirme que as quatro fontes aparecem como processadas antes de continuar.

## 3. Configurar a diretriz

Abra a configuração de resposta ou personalização do chat e cole:

```text
Atue como um especialista e professor de IA generativa aplicada ao desenvolvimento de software. Responda exclusivamente com base nas fontes deste notebook. Explique os conceitos de forma clara para uma pessoa iniciante em tecnologia, sem omitir detalhes importantes. Em cada resposta, apresente as citações correspondentes. Diferencie fatos apresentados pelas fontes, conclusões dos autores e inferências. Se as fontes não trouxerem informação suficiente, diga isso explicitamente. Ao tratar de produtividade, segurança ou qualidade, compare benefícios, limitações e riscos e não apresente alegações promocionais como consenso científico.
```

## 4. Fazer as perguntas e registrar evidências

Faça uma pergunta por vez. Após cada resposta:

1. confira se aparecem citações numeradas;
2. clique em pelo menos uma citação para confirmar que abre o trecho correto;
3. tire um print contendo a pergunta, a resposta e as citações;
4. salve usando o nome indicado;
5. copie a resposta e os nomes das fontes para me enviar.

Perguntas:

1. `O que é IA generativa e como ela se diferencia de outras formas de aprendizado de máquina?`
   Print: `pergunta-01.png`
2. `Em quais etapas do desenvolvimento de software a IA generativa pode ajudar? Dê exemplos baseados nas fontes.`
   Print: `pergunta-02.png`
3. `Quais evidências as fontes apresentam sobre ganhos de produtividade e quais limitações devem ser consideradas ao interpretar essas evidências?`
   Print: `pergunta-03.png`
4. `Quais riscos surgem ao usar IA generativa para produzir ou revisar código? Relacione a resposta às recomendações do NIST.`
   Print: `pergunta-04.png`
5. `Crie uma lista de práticas que um desenvolvedor iniciante deve seguir para usar IA generativa com responsabilidade, segurança e senso crítico.`
   Print: `pergunta-05.png`
6. `Compare as fontes: em quais pontos elas concordam, se complementam ou apresentam perspectivas diferentes? Considere também que Google e GitHub oferecem produtos relacionados ao tema.`
   Print: `pergunta-06.png`

Salve os prints na pasta `evidencias` deste projeto.

## 5. Gerar materiais no Estúdio

No Estúdio, gere os formatos disponíveis abaixo:

- **Mapa mental:** visão geral dos conceitos, usos, benefícios, riscos e boas práticas. Salve como `mapa-mental.png`.
- **Apresentação/slides:** apresentação introdutória sobre IA generativa no desenvolvimento de software. Salve como `slides.pdf`.
- **Guia de estudos:** inclua resumo, glossário, perguntas de revisão e quiz. O arquivo gerado foi salvo como `guia-de-estudos.docx`.
- **Resumo em áudio:** enfoque em benefícios, limitações e uso responsável. O arquivo gerado foi salvo como `resumo-em-audio.m4a`.

Coloque os arquivos baixados na pasta `materiais`.

## 6. Compartilhar o notebook

1. Clique em **Compartilhar**.
2. Habilite o acesso por link na modalidade permitida pela sua conta.
3. Copie o link.
4. Abra uma janela anônima e confirme que o notebook pode ser acessado.
5. Envie o link junto com as respostas e os prints para finalizar o README.

## O que me enviar para a finalização

- link compartilhado do notebook;
- texto das seis respostas;
- nomes das fontes citadas em cada resposta;
- seis prints do chat com as citações visíveis;
- mapa mental, slides, guia de estudos e áudio que conseguir baixar.

Com esses itens, os campos pendentes do `README.md` podem ser substituídos por evidências reais.
