# ARO UA — Avaliação de Risco Operacional

**➡️ Abrir a aplicação: <https://alexdimas238.github.io/aro-ua/>**

Ferramenta para elaborar e emitir a **Avaliação de Risco Operacional (ARO)** de operações com
**UA (aeronave não tripulada)**, em cumprimento ao **RBAC 100** da ANAC, usando a matriz de
risco 5×5 da **IS nº E94-003 Revisão A**.

Funciona no celular, no tablet e no computador. **Sem login e sem cadastro** — não existe
conta a criar nem servidor guardando o que você digita.

## Como usar

1. Abra o link acima. Para usar em campo sem sinal, veja *Uso sem internet* abaixo.
2. Preencha nome, CPF e SARPAS — ficam salvos para as próximas AROs.
3. A data já vem preenchida e a validade é calculada em 12 meses automaticamente.
4. Descreva o cenário e a UA.
5. Adicione quantas situações de risco precisar. Escolha probabilidade e severidade pelos
   botões, ou toque direto na matriz 5×5.
6. Registre as medidas de mitigação.
7. Assine na tela com o dedo.
8. Toque em **Gerar PDF**.

O PDF sai pronto para assinatura e arquivo, com o verso oficial preservado.

## Seus dados não saem do seu aparelho

Não há back-end, banco de dados, conta de usuário nem telemetria. Tudo — inclusive a sua
assinatura — fica salvo apenas no navegador do seu próprio aparelho, e o PDF é montado
localmente. Nada é enviado para lugar nenhum.

Por isso, **limpar os dados do navegador apaga o histórico**. Use
**Configurações → Exportar backup** de tempos em tempos.

## Uso sem internet

A aplicação **precisa de internet para abrir**. Ela não se instala no aparelho: salvar o link
nos favoritos ou na tela de início guarda apenas o endereço, não a aplicação. Se você abrir
esse atalho sem sinal, o navegador vai acusar falta de conexão.

Para levar a ARO a campo, **salve a página, não o link**:

- **Computador:** `Ctrl+S` (Windows) ou `Cmd+S` (Mac) e guarde o arquivo `.html`.
- **Android:** menu ⋮ → ícone de download.

São cerca de 110 KB num arquivo só. Abrindo esse arquivo direto do aparelho, sem rede nenhuma,
o formulário, a matriz 5×5, a assinatura e a **geração do PDF funcionam normalmente**.

Duas ressalvas nessa cópia salva:

- **A aba Normas não abre.** Os três PDFs são arquivos separados. Baixe cada um pelos botões
  *Baixar* enquanto estiver com internet, se quiser consultá-los depois.
- **O histórico não é compartilhado com o site.** O navegador trata o endereço na internet e o
  arquivo local como dois armazenamentos distintos. Para levar suas AROs, UA cadastradas e
  configurações de um para o outro, use *Configurações → Exportar backup* e depois
  *Importar backup*.

## Normas disponíveis na aplicação

A aba **Normas** traz, na íntegra, para leitura na tela ou download:

- **RBAC 100 / RBAC-E nº 94** (ANAC) — exigência da ARO atualizada nos últimos 12 meses
- **IS nº E94-003 Revisão A** (ANAC) — matriz 5×5, níveis de probabilidade e severidade
- **ICA 100-40** (DECEA) — acesso ao espaço aéreo e SARPAS

São atos normativos oficiais, reproduzidos sem alteração. Confirme sempre a versão vigente em
[gov.br/anac](https://www.gov.br/anac) e [decea.mil.br](https://www.decea.mil.br).

## Aviso

A ferramenta **auxilia** o registro e a classificação do risco. Ela **não autoriza nem impede**
a realização de operação alguma — não há lógica de GO/NO-GO. A decisão de operar, a exatidão
das informações e o cumprimento da regulamentação são de responsabilidade exclusiva do piloto
remoto, do operador e da autoridade competente.

## Licença

Uso da aplicação livre e gratuito. Cópia, redistribuição, hospedagem em outro endereço e
modificação **não** são autorizadas — veja [LICENSE](LICENSE).

Este repositório contém apenas o arquivo publicado. O código-fonte não é público.

---

Desenvolvido por **Alexandre Dimas**
[dimas.ppsarp@gmail.com](mailto:dimas.ppsarp@gmail.com) · [github.com/AlexDimas238](https://github.com/AlexDimas238)

© 2026 Alexandre Dimas. Todos os direitos reservados.
