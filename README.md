# LocaHub — versões oficiais

Este repositório distribui os instaladores, a versão portátil e as notas de atualização do LocaHub para Windows x64. O código do aplicativo e do serviço de licenças e atendimento fica em repositório privado.

Para uma instalação nova, use **[LocaHub-Instalar.exe](https://github.com/mateusartur27/gestao-locacoes-atualizacoes/releases/latest/download/LocaHub-Instalar.exe)**, o instalador online de aproximadamente 45 KB. Ao clicar em Instalar, ele consulta a versão estável mais recente, baixa o instalador completo, confere tamanho e SHA-256 e inicia a instalação. Precisa de internet. O mesmo arquivo pode ser reutilizado para as próximas versões do aplicativo, enquanto a distribuição e os requisitos do próprio instalador permanecerem compatíveis. O checksum específico fica em LocaHub-Instalar.sha256.

A alternativa **LocaHub-Instalador.exe** contém uma versão completa e instala a versão que estava incluída quando foi baixado. Ambos utilizam o mesmo processo de instalação do aplicativo, que cria os atalhos, inclui o runtime .NET e oferece instalar o Microsoft Edge WebView2 Runtime quando necessário. O online usa o .NET Framework 4.x já incluído no Windows 10/11.

Os arquivos ficam na [página de versões](https://github.com/mateusartur27/gestao-locacoes-atualizacoes/releases). A distribuição 0.31.4 inclui o instalador online 1.0.1, com instrução inicial mais direta e botão Tentar novamente ajustado ao texto. As versões anteriores continuam disponíveis. Quem já usa o aplicativo pode atualizar pelo próprio LocaHub; o instalador online serve para novas instalações e reinstalações.

Na edição portátil, extraia toda a pasta e abra **LocaHub.exe** na raiz. A pasta `current`, o componente auxiliar `Update.exe` e os demais arquivos precisam permanecer juntos. `Update.exe` aplica as atualizações; ele não é o aplicativo nem o instalador.

Desde a versão 0.30.0, o aplicativo avisa quando há uma atualização. Você pode consultar as mudanças, baixar e escolher quando atualizar e reiniciar. O download não aplica a atualização sozinho. Versões anteriores à 0.30.0 precisam receber uma distribuição compatível uma vez para habilitar esse fluxo.

Dados, usuários e licença ficam separados dos arquivos do programa e são preservados nas atualizações. Continue mantendo seus backups externos. É necessária uma licença comercial para usar o sistema.

O instalador online consulta versões já publicadas; ele não publica novas versões. A publicação dos pacotes continua sendo uma etapa explícita após os testes do código privado.

SHA256SUMS.txt e releases.win.json permitem conferir a integridade dos pacotes do aplicativo. LocaHub-Instalar.sha256 cobre o instalador online adicional. Os executáveis ainda não têm assinatura Authenticode.
