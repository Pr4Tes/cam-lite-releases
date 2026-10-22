# Cam Lite — distribuição oficial

Pacotes de atualização para Windows instalado, Windows Portable e Linux x64. As fontes de desenvolvimento permanecem privadas.

## Downloads

Consulte [Releases](https://github.com/Pr4Tes/cam-lite-releases/releases) para as versões publicadas. Escolha somente o pacote correspondente à sua modalidade. Mantenha todas as bibliotecas e o ajudante de atualização junto do aplicativo.

A passagem da versão 2.1.3 para 2.2.0 exige instalar o pacote uma vez. Depois, use **Configurações → Atualizações**. Consultas e downloads mantêm o monitoramento; a instalação exige confirmação e pode reiniciar a visualização.

## Autenticidade

Cada modalidade possui um manifesto próprio (`version-windows-installer.json`, `version-windows-portable.json` ou `version-linux.json`) e uma assinatura `.sig`. O aplicativo verifica a assinatura RSA dos bytes exatos do manifesto, sua validade, plataforma, modalidade, tamanho e SHA-256 do pacote. A chave pública está incorporada ao aplicativo. Nenhuma chave privada ou credencial é distribuída aqui.

Confira também `SHA256SUMS.txt`, notas e instruções de cada release. Não execute um pacote cuja integridade não corresponda à publicação oficial.

## Validação

Os testes e limitações são informados nas notas. Compilar o pacote Linux não substitui executá-lo no Debian do equipamento de referência. Confirmar a abertura da interface não comprova as conexões das câmeras.
