<a id="descricao"></a>
    <h1 align="center">Descrição 🤖</h1>
Projeto desenvolvido junto à <strong><a href="https://github.com/Rocketseat">@Rocketseat</a></strong> na <em>Next Level Week I.A</em> durante os dias 11 à 14 de Setembro de 2023.
   O site <strong><em>Tell Me</em></strong> tem como objetivo transcrever e resumir o conteúdo falado nos vídeos de curta duração do youtube (<em>shorts</em>). Esta ferramenta tem sua capacidade e funcionalidade escalável, podendo assim ser usada de diversas formas para atender a diferentes necessidades.
<hr>

<p align="center">
	<a href="#tecnologias">Tecnologias</a> •
	<a href="#dependencias">Dependências</a> • 
	<a href="#iniciar">Iniciar</a> • 
	<a href="#metodo">Método</a>
</p>

<hr>
<a id="tecnologias"></a>
    <h1 align="center">Tecnologias utilizadas neste projeto 🖥️</h1>
<br>
<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
  <li>Node.js</li>
  <li>Inteligências Artificiais Whisper e Bart</li>
</ul>
<hr>
<a id="dependencias"></a>
    <h1 align="center">Instalação das dependências 👨‍💻</h1>
<hr>
<strong>OBS: Necessário possuir o NodeJS na sua máquina.</strong>
<br>
<br>
<p>No terminal, digite:</p>
  <li>Instalar o Npm:</li>
  <ul> 
    
`npm run i`  

Surgirá a pasta *node_modules*
<hr>
<a id="iniciar"></a>
    <h1 align="center">Iniciar aplicação 🔌</h1>
<br>
<p>No terminal:</p>
<li>Iniciar Servidor:</li>

`npm run server`
<br>
<li>Iniciar Web:</li>

`npm run web`
<br>

Acesse o link *localhost* indicado no terminal
<br>
<br>
    <strong>*Tell Me está pronto para ser usado*.</strong>
  </ul>
<hr>
<a id="metodo"></a>
    <h1 align="center">Método de funcionamento 🔍</h1>
<ul>
<br>
	
- O usuário copiará o link do *short* que será resumido e dará o *input* no site;

- Após validar o vídeo, o programa irá baixar o arquivo em formato `.mp4`;

- O formato do arquivo será convertido para áudio `.wav`;

- Será iniciado o processo de transcrição do que foi falado (Ignorando músicas de fundo) por meio do *whisper*;

- A transcrição será resumida por meio do *bart*;

- O resumo será mostrado no navegador.

  <p align="center">
        <a href="#descricao">Voltar ao Início</a>
    </p>
