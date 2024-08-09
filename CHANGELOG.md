## [2.2.2] - 08-08-2024
- Correção: Remoção de lib (playstore-dynamic-feature) que não possui suporte a Android 14.

## [2.2.1] - 04-03-2024
- Melhoria: Atualização da biblioteca MLKit (17.1.0).

## [2.2.0] - 07-12-2024
- Melhoria: Retornar erros via callback (callbackProcessamentoLiveness).
- Melhoria: Adicionado novo certificado sslpinning 

## [2.1.2] - 07-12-2023
- Melhoria: Adicionado novo certificado sslpinning .

## [2.1.1] - 17-08-2023
- Melhoria: Tela de Erro customizável.
- Melhoria: Inclusão de Tratamento dos erros de conexão e comunicação.

## [2.0.1] - 16-02-2023
- Correção: Envio de metadados para analise e processamento.
- Correção: Remoção da vibração no processo de captura.

## [2.0.0] - 27-01-2023
- Melhoria: atualização de layout para nova experiência com acessibilidade.
- Melhoria: ícones de telas customizáveis.
- Melhoria: inclusão de ícone de confirmação para captura.
- Melhoria: inclusão de vibração no processo de captura.

## [1.3.0] - 30-11-2022
- Melhoria: Retorno da flag SSLPinning.
- Melhoria: Inclusão de novo certificado.

## [1.2.3] - 04-11-2022
- Melhoria: Depreciação da flag SSLPinning.

## [1.2.2] - 07-10-2022
- Correção: Remoção captura trilha de acelerômetro.

## [1.2.1] - 29-06-2022
- Correção: flag (tipoRetorno) valor default base64.

## [1.2.0] - 27-06-2022
- Melhoria: Adicionado o envio de metadados para analise e processamento.
- Melhoria: Validação de funcionamento do acelerômetro.
- Melhoria: Incluído customização(via xml ou na inicialização do componente) do texto do acelerômetro.

## [1.1.9] - 31-05-2022
- Melhoria: Ajuste na dimensões do oval de referência.
- Melhoria: Redução da imagem para analise e melhoria na performance.
- Correção: Processo com delay 0 e tempo de captura da selfie fixo.
- Melhoria: Modificado flag (tempoDelayMensagem) para 0ms como default
- Melhoria: Mudança flag (tempoDelayMensagem) depreciada
- Melhoria: Adicionado variáveis para obtenção de métricas.

## [1.1.8] - 10-05-2022
- Correção: Customização de texto de orientação(permitir alteração da cor do texto).

## [1.1.7] - 05-05-2022
- Melhoria: Alteração apontamento para validar chave document.brscan.com.br/v1/.
- Melhoria: Adicionado flag (segurancaExtraEmulatorCheck) para validar se o dispositivo é um emulador.

## [1.1.6] - 25-04-2022
- Melhoria: Adicionado flag (tempoDelayMensagem) define o tempo de exibição entre as mensagem de processo(2000ms default).
- Melhoria: Adicionado flag (acessibilidade) que habilita recurso de acessibilidade A+
- Melhoria: Incluído customização(via xml) de cores texto e caixa de orientações na tela de captura.
- Melhoria: Incluído customização(via xml) de tamanho texto de orientações na tela de captura.
- Melhoria: Adicionado meta no Manifest para DEPENDENCIES do mlkit.

## [1.1.5] - 18-04-2022
- Melhoria: Removido meta do retorno de tipo "base64" data:image/jpeg;base64.

## [1.1.4] - 12-04-2022
- Melhoria: Otimização no uso de memória.

## [1.1.3] - 04-04-2022
- Melhoria: Mudança flag (resolucao) depreciada.
- Melhoria: A resolução para todo o processo de validação e retorno é a "Low", dimensão 720x1280.
- Melhoria: Incluído meta do retorno de tipo "base64" data:image/jpeg;base64.
- Melhoria: No retorno com erro será retornado o Código do erro, iD da analise e a Descrição.
- Melhoria: Incluído parametrização da cor do backgroung do frame de loading
- Melhoria: Incluído parametrização da cor do botão dos frames.
- Melhoria: Incluído parametrização da cor do Check das instruções.

## [1.1.2] - 28-03-2022
- Melhoria: Adicionado flag (retornarErros) retornar todos os erros para aplicação cliente.
- Melhoria: Mudança flag (segurancaExtra) depreciada.
- Melhoria: Adicionado flag (segurancaExtraRootCheck) para validar se o dispositivo está no modo root.
- Melhoria: Adicionado flag (segurancaExtraSslPinning) para validar ssl pinning.
- Melhoria: Reiniciar processo de captura quando não identificar rosto ou identificar mais de um.

## [1.1.1] - 17-03-2021
- Melhoria: Adicionado botão de fechar na tela inicial (quando wizard for true) que possibilitar sai do sdk.
- Melhoria: Alteração no botão de fechar da tela de captura para um x da cor preta.
- Melhoria: Alteração da cor do oval da tela de captura para cor secondary (magenta).
- Melhoria: Adicionando no objeto de retorno o id da captura.

## [1.1.0] - 09-02-2021
- Melhoria: Adicionado flag (performance) para habilitar/desabilitar performance
- Melhoria: Adicionado flag (verificarOlhos) para habilitar/desabilitar a validação dos olhos abertos
- Melhoria: Adicionado flag (tipoRetorno) para escolher entre base64 ou path do arquivo
- Melhoria: Não salva imagem quando o tipo de retorno é base64
- Melhoria: Mudança no objeto de retorno (removendo campos path e base64 e adicionando campo imagem)
- Melhoria: Adicionado flag (configuracaoTexto) para receber os textos de customização

## [1.0.26] - 07-12-2021
- Melhoria: Adicionado telas de instruções para captura com iconografia.
- Melhoria: Cor de fundo de captura.
- Melhoria: Adicionado tela de sucesso com imagem de selfie.
- Melhoria: Atualização de certificado ssl pinning liveness.
- Melhoria: Adicionado flag de habilitar modo swiper de telas de instruções.
- Melhoria: Ajuste no código para fluxo de telas.

## [1.0.25] - 17-11-2021
- Melhoria: Correções de segurança.