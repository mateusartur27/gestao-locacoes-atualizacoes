# LocaHub — versões oficiais

Este repositório distribui os instaladores, a versão portátil e as notas de atualização do LocaHub para Windows x64. O código do aplicativo e do serviço de licenças e atendimento fica em repositório privado.

Os arquivos ficam na [página de versões](https://github.com/mateusartur27/gestao-locacoes-atualizacoes/releases). Para uma instalação nova, use **LocaHub-Instalador.exe** nas versões mais recentes. O instalador cria os atalhos, inclui o runtime .NET e oferece instalar o Microsoft Edge WebView2 Runtime quando necessário.

Na edição portátil, extraia toda a pasta e abra **LocaHub.exe** na raiz. A pasta `current`, o componente auxiliar `Update.exe` e os demais arquivos precisam permanecer juntos. `Update.exe` aplica as atualizações; ele não é o aplicativo nem o instalador.

Desde a versão 0.30.0, o aplicativo avisa quando há uma atualização. Você pode consultar as mudanças, baixar e escolher quando atualizar e reiniciar. O download não aplica a atualização sozinho. Versões anteriores à 0.30.0 precisam receber uma distribuição compatível uma vez para habilitar esse fluxo.

Dados, usuários e licença ficam separados dos arquivos do programa e são preservados nas atualizações. Continue mantendo seus backups externos. É necessária uma licença comercial para usar o sistema.

Os arquivos SHA256SUMS.txt e releases.win.json permitem conferir a integridade dos downloads. Os executáveis ainda não têm assinatura Authenticode.
