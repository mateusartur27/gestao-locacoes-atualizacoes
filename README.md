# LocaHub — versões oficiais

Este repositório distribui os instaladores, a versão portátil e as notas do LocaHub para Windows x64. O código do aplicativo e do servidor fica em repositório privado.

Para uma instalação nova, use **[LocaHub-Instalar.exe](https://github.com/mateusartur27/gestao-locacoes-atualizacoes/releases/latest/download/LocaHub-Instalar.exe)**, o instalador online de aproximadamente 53 KB. Ele mostra a pasta de instalação preenchida, permite digitar ou escolher outra pasta vazia e gravável pelo usuário, consulta a versão estável mais recente, baixa o instalador completo e confere tamanho e SHA-256 antes de executá-lo. Precisa de internet. Se já existir uma instalação em outra pasta, desinstale-a mantendo os dados antes de mudar o destino.

O mesmo arquivo online pode buscar futuras versões do app enquanto a distribuição e os requisitos do próprio instalador permanecerem compatíveis. Um arquivo online antigo não muda sua própria interface: baixe o novo para receber alterações no assistente. O checksum específico fica em LocaHub-Instalar.sha256.

A alternativa **LocaHub-Instalador.exe** contém uma versão completa e instala a versão incluída quando foi baixado. O processo cria atalhos, inclui o runtime .NET do app e oferece instalar o Microsoft Edge WebView2 Runtime quando necessário. O online e o assistente de desinstalação usam o .NET Framework 4.x incluído no Windows 10/11.

A [versão 0.32.0](https://github.com/mateusartur27/gestao-locacoes-atualizacoes/releases/tag/v0.32.0) inclui o online 1.1.0, termos de uso e licença na ativação com aceite explícito registrado no servidor, consulta dos termos nas Preferências e assistente de desinstalação com exclusão opcional de dados. O texto inicial dos termos ainda requer revisão jurídica/comercial antes da venda. Fabricante atual: Mateus Artur; produto: LocaHub.

Ao abrir a versão instalada, o aplicativo registra seu assistente na opção Desinstalar do Windows. Ele também fica em current/LocaHub-Desinstalar.exe. Os dados são mantidos por padrão. Excluí-los exige marcar a opção e confirmar: remove dados, usuários, ativação, preferências e cópias internas somente deste perfil do Windows, depois de concluir a desinstalação. Backups externos, licença no servidor e conversas na nuvem permanecem. A remoção direta por Update.exe conserva os dados.

Na edição portátil, extraia toda a pasta e abra **LocaHub.exe** na raiz. Mantenha current, Update.exe e os demais arquivos juntos. O assistente de desinstalação reconhece instalações; o portátil é removido pela própria pasta. Os dados ficam separados dela.

Desde a 0.30.0, o app avisa quando há atualização. Você pode consultar as novidades, baixar e escolher quando atualizar e reiniciar. O download não aplica a atualização sozinho. Versões anteriores precisam receber uma distribuição compatível uma vez.

Dados e usuários ficam fora dos arquivos substituídos pelo atualizador. Mantenha backups externos. É necessária uma licença comercial para usar o sistema. As versões anteriores continuam disponíveis.

O instalador online consulta versões publicadas; ele não publica versões. A publicação dos pacotes continua explícita após os testes do código privado. SHA256SUMS.txt, releases.win.json e LocaHub-Instalar.sha256 permitem conferir a integridade. Os executáveis ainda não têm assinatura Authenticode; a homologação interativa e os preparativos comerciais continuam pendentes.
