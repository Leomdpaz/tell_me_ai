<h1 align="center">Descrição 🤖</h1> 
Projeto desenvolvido junto à <strong><a href="https://github.com/Rocketseat">@Rocketseat</a></strong> na _Next Level Week I.A_ durante os dias 11 à 14 de Setembro de 2023.
   O site ***Tell Me*** tem como objetivo transcrever e resumir o conteúdo falado nos vídeos de curta duração do youtube *(shorts)*. Esta ferramenta tem sua capacidade e funcionalidade escalável, podendo assim ser usada de diversas formas para atender a diferentes necessidades.
<hr>
<p align="center">
 <a href="Tecnologias utilizadas neste projeto 🖥️">Tecnologias</a> •
 <a href="Instalação das dependências 👨‍💻">Dependências</a> • 
 <a href="Iniciar aplicação 🔌">Iniciar</a> • 
 <a href="Método 🔍">Método</a> 
</p>
<hr>
<h1 align="center">Tecnologias utilizadas neste projeto 🖥️</h1>
<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
  <li>Node.js</li>
  <li>Inteligências Artificiais Whisper e Bart</li>
</ul>
<hr><h2 align="center">Instalação das dependências 👨‍💻</h2>
<hr>
<strong>OBS: Necessário possuir o NodeJS na sua máquina.</strong>
<br>
<br>
<p>No terminal, digite:</p>
  <li>Instalar o Npm:</li>
  
  <ul> 
    
`npm run server`  

Surgirá a pasta *node_modules*
<hr>
<h1 align="center">Iniciar aplicação 🔌</h1> 
<br>
<p>No terminal, digite:</p>
  <li>Iniciar Servidor:</li>
    
`npm run server`
	<br>
	<li>Iniciar Web:</li>
    
`npm run web`

Acesse o link *localhost* indicado no terminal
<br>
<br>
    <strong>*Tell Me está pronto para ser usado*.</strong>
  </ul>
<hr>
<h1 align="center">Método 🔍</h1> 
<ul>
  
- O usuário copiará o link do *short* que será resumido e dará o *input* no site;

- Após validar o vídeo, o programa irá baixar o arquivo em formato `.mp4`;

- O formato do arquivo será convertido para áudio `.wav`;

- Será iniciado o processo de transcrição do que foi falado (Ignorando músicas de fundo) por meio do *whisper*;

- A transcrição será resumida por meio do *bart*;

- O resumo será mostrado no navegador.



