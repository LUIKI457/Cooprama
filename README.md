# Cooprama
6 minigames cooperativos de papel (2 a 4 jogadores), PWA, online sem servidor próprio.

1. Suba todos os arquivos na raiz de um repositório do GitHub.
2. Settings > Pages > Deploy from branch (main, /root).
3. Abra o link no celular > "Adicionar à tela inicial".

Online: uma pessoa toca em "Criar sala" e passa o código de 4 letras; os outros tocam em "Entrar".
Usa a biblioteca PeerJS (conexão direta entre celulares) e o serviço gratuito de salas deles, então
se o serviço estiver fora do ar, "Criar sala" avisa e "Jogar sozinho" continua funcionando.
