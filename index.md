olítica de Privacidade — Meu Álbum 2026
Última atualização: 08 de maio de 2026

Esta Política de Privacidade descreve como o aplicativo Meu Álbum 2026 ("aplicativo", "nós") coleta, utiliza e protege os dados dos usuários ("você"), em conformidade com a Lei Geral de Proteção de Dados (LGPD — Lei nº 13.709/2018), com a Lei Geral de Proteção de Dados de Crianças e Adolescentes, e com as exigências da Apple App Store e do Google Play.

1. Quem somos
O aplicativo é desenvolvido e mantido por Marcio Fernando Delalibera Chaves, pessoa física, como projeto pessoal sem fins lucrativos.

Contato: mpcx13x@gmail.com

2. Dados que coletamos
2.1. Dados fornecidos diretamente por você
Nome de usuário (username escolhido por você no cadastro — pode ser fictício)
PIN numérico opcional (4 a 6 dígitos, usado apenas para recuperar a conta caso troque de aparelho)
Não coletamos: e-mail, nome real, telefone, endereço, foto, dados financeiros, dados de saúde nem documento de identidade.

2.2. Dados de uso do app
Coleção de figurinhas (quais figurinhas você tem, marcou como repetida, etc.)
Conquistas desbloqueadas
Bolões que você criou ou participa, palpites realizados
Lendas Extras desbloqueadas no pacote diário
Pontos acumulados, sequência (streak) de dias consecutivos abrindo o app
Eventos analíticos de uso (descritos em detalhe na seção 2.5)
Esses dados são vinculados ao seu nome de usuário para sincronização e para que sua coleção seja preservada caso você troque de aparelho.

2.3. Localização (opcional)
Localização aproximada (cidade e estado), apenas se você autorizar quando solicitado.
Usada exclusivamente para sugerir grupos regionais de troca de figurinhas.
Você pode negar e o app continua funcionando normalmente, sem essa funcionalidade.
Não coletamos sua localização precisa (coordenadas GPS).
2.4. Dados processados localmente (não enviados aos nossos servidores)
Fotos tiradas pela câmera do aplicativo são processadas inteiramente no seu dispositivo para reconhecimento das figurinhas (OCR via Google ML Kit on-device). As imagens não são armazenadas, nem enviadas a nenhum servidor.
Fotos da galeria (caso você opte por essa entrada): igualmente processadas no seu próprio dispositivo, sem envio.
2.5. Eventos analíticos de uso
Para entender como o app é utilizado e priorizar melhorias, registramos os seguintes eventos vinculados ao seu nome de usuário:

Evento	Quando ocorre	Dados associados
app_open	Cada abertura do app	data/hora
tela_visitada	Você navega entre telas principais	nome da tela, data/hora
figurinha_marcada	Você marca/desmarca uma figurinha	número da figurinha, seleção, ação
pacote_aberto	Você abre um pacote diário	tipo do pacote (diário/easter), data/hora
bolao_criado	Você cria um bolão	modo (solo/grupo), data/hora
palpite_salvo	Você dá um palpite num jogo	id do jogo, se foi dobrada, data/hora
easter_egg_descoberto	Você descobre um easter egg	qual easter egg, data/hora
banner_clicado	Você toca em banner promocional	id do banner, data/hora
ultimo_acesso	Atualizado a cada uso	data/hora
Não coletamos:

Conteúdo de mensagens, fotos pessoais, contatos, agenda, microfone, áudio
Identificadores de propaganda (IDFA / Advertising ID) — desativado completamente
Identificadores únicos do dispositivo (UDID, device fingerprint)
Histórico de navegação fora do app
Dados de outros aplicativos no seu dispositivo
3. Como usamos seus dados
Os dados são utilizados exclusivamente para:

Permitir o cadastro e o login na sua conta
Sincronizar sua coleção, bolões e progresso entre aparelhos
Calcular rankings, conquistas, sequências e estatísticas
Sugerir grupos de troca regionais (se você compartilhou localização)
Entender padrões de uso para melhorar o app (eventos analíticos da seção 2.5)
Diagnosticar e corrigir erros do app
Cumprir obrigações legais
Não utilizamos seus dados para:

Anúncios direcionados ou personalizados
Venda a terceiros
Compartilhamento com data brokers
Rastreamento entre aplicativos (cross-app tracking)
Análise comportamental para perfis publicitários
4. Com quem compartilhamos seus dados
Não compartilhamos seus dados pessoais com terceiros para fins comerciais.

A infraestrutura do app é operada diretamente pelo desenvolvedor:

Serviço	Finalidade	Local
Banco de dados próprio (PostgreSQL)	Armazenar coleção, conta, bolões, eventos	Brasil (servidor pessoal)
Cloudflare Tunnel	Disponibilizar a API publicamente via HTTPS	Distribuído globalmente
GitHub Pages	Hospedar esta política de privacidade pública	Distribuído globalmente
A Cloudflare apenas roteia tráfego HTTPS — não armazena conteúdo dos dados pessoais.

4.1. Banner promocional
O app exibe ocasionalmente banner promocional de produto vendido em loja parceira (Mercado Livre). Quando você toca no banner, o sistema operacional abre o navegador externo do seu celular e direciona ao site da loja com parâmetros UTM padrão (utm_source=app&utm_campaign=appcopa). Quem registra essa visita é o site da loja, não o app. O app não envia dados pessoais ao Mercado Livre.

5. Armazenamento e segurança
Os dados são armazenados em servidor próprio com criptografia em trânsito (HTTPS via Cloudflare TLS 1.3) e em repouso (PostgreSQL com cifragem do disco).
O acesso administrativo é restrito ao desenvolvedor responsável, autenticado.
O PIN, quando você opta por cadastrá-lo, é armazenado em formato hashed (não em texto puro) no servidor e em Keychain/Keystore criptografado no seu aparelho.
Token de sessão fica armazenado em Apple Keychain (iOS) ou Android Keystore (Android) — nunca em texto puro.
6. Retenção dos dados
Sua coleção, bolões e progresso ficam armazenados enquanto você usar o app ou até você solicitar a exclusão.
Eventos analíticos são mantidos por 180 dias após a coleta. Após esse prazo são automaticamente apagados ou agregados de forma anônima (sem possibilidade de identificar usuário individual).
Backup completo da conta pode ser baixado em formato JSON a pedido (envie e-mail).
7. Seus direitos (LGPD)
Você pode, a qualquer momento, solicitar:

Acesso aos seus dados (relatório completo do que temos sobre você)
Correção de dados incorretos
Exclusão total da sua conta e de todos os dados associados
Portabilidade dos dados em formato legível (JSON)
Anonimização (manter coleção mas remover associação com seu username)
Informações sobre com quem compartilhamos seus dados
Revogar consentimento para coleta de localização (basta desativar nos Ajustes do celular)
Para exercer qualquer desses direitos, envie um e-mail para mpcx13x@gmail.com com o assunto "LGPD" e seu nome de usuário. Responderemos em até 15 dias.

8. Crianças e adolescentes
O aplicativo é classificado para idade livre (4+) mas é destinado preferencialmente a usuários com 13 anos ou mais.

Não coletamos intencionalmente dados pessoais de crianças menores de 13 anos sem consentimento dos pais ou responsáveis.
Como o cadastro requer apenas um username escolhido pelo próprio usuário (sem e-mail), uma criança pode utilizar o app de forma anônima sem fornecer dados sensíveis.
Caso identifiquemos coleta inadvertida de dados de criança menor de 13 anos sem autorização, todos os dados serão excluídos imediatamente.
Pais ou responsáveis que detectem uso inadequado podem solicitar exclusão imediata enviando e-mail para mpcx13x@gmail.com.
9. Permissões do dispositivo
O aplicativo solicita as seguintes permissões:

Câmera: para fotografar páginas do álbum e reconhecer figurinhas. As imagens nunca são enviadas aos nossos servidores — todo processamento é local. Você pode negar e usar a entrada manual.
Localização (Quando em Uso): opcional, para sugerir grupos de troca regionais. Você pode negar.
Galeria de Fotos: opcional, para escolher imagem do álbum em vez de usar câmera. Você pode negar.
Internet: necessária para sincronização da conta, bolões, ranking e eventos analíticos.
10. Tracking entre aplicativos (App Tracking Transparency — Apple)
Não realizamos tracking entre aplicativos. Especificamente:

Não usamos IDFA (Identifier for Advertisers) — não acessamos esse dado.
Não exibimos prompt de App Tracking Transparency.
Não vinculamos sua atividade no nosso app com sua atividade em outros apps ou sites.
Não compartilhamos dados com data brokers ou redes publicitárias.
Pela definição da Apple, não somos um app que rastreia usuários.

11. Alterações nesta Política
Esta Política pode ser atualizada periodicamente quando:

Adicionarmos novas funcionalidades que coletam novos dados
Houver mudanças regulatórias (LGPD, CCPA, GDPR, etc.)
Identificarmos a necessidade de detalhar melhor algum item
Alterações significativas serão comunicadas dentro do aplicativo. A data da última atualização aparece no topo deste documento.

12. Marcas registradas
Este aplicativo não é afiliado, patrocinado ou endossado pela FIFA, pela Panini, pela CBF ou por qualquer entidade oficial relacionada à Copa do Mundo. Os nomes, logos e símbolos das seleções e da Copa pertencem aos seus respectivos titulares.

13. Contato
Dúvidas sobre esta Política, exercício de direitos LGPD, ou denúncias de incidente de segurança:

E-mail: mpcx13x@gmail.com

Tempo de resposta: até 15 dias úteis.
