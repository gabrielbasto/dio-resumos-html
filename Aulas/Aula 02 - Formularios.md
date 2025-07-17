## Introdução ao HTML

### Tags <form> e seus modificadores
|Tag|Modificador|Função|
|---|---|---|
|```<form>```|---|Adiciona um campo do tipo formulário.|
|```<form>```|```name=""```|Dá nome ao formulário, como um identificador.|
|```<form>```|```action=""```|URL Para onde os dados serão enviados.|
|```<form>```|```method=""```|Indica o método de envio desse formulário, podendo ser enviado através do comando ```get``` ou ```post```.|
|---|```method="get"```|Envia a informação via URL do navegador *(O que faz com que não seja seguro)*.|
|---|```method="post"```|Envia a informação via ```<body>``` com uma requisição ao servidor.|
|```<form>```|```target=""```|Informa se o envio será feito, assim como em uma tag ```<a>```.|
|---|```<target="self">```|Faz o envio através da mesma página no navegador.|
|---|```<target="_blank">```|Faz o envio através de uma nova aba no navegador.|
|```<form>```|```autocomplete=""```|Determina se os campos salvarão os dados enviados no navegador. São utilizados dos comandos: ```on``` e ```off```.|
|```<form>```|```onsubmit=""```|Adiciona o evento de quando o formulário for enviado. O comando é declarado via Javascript|

### Tags <input> e seus modificadores

|Tag|Modificador|Função|
|---|---|---|
|```<input>```|---|Adiciona um campo ao formulário.|
|```<input>```|```type=""```|Indica o tipo do input informado.|
|---|```type="text"```|Input do tipo texto padrão.|
|---|```type="number"```|Input do tipo númerico, só permitindo a entrada de números. Existem modificadores como: ```min=""```, ```max=""```, ```step=""```.|
|---|```type="button"```|Input do tipo botão. Acompanha o modificador ```value=""``` para indicar o título do botão.|
|---|```type="range"```|Input do tipo "volume" permitindo a atribuição do valor.|
|---|```type="color"```|Input do tipo de cor, ao qual aparece o seletor de cores.|
|---|```type="email"```|Input do tipo texto voltado para e-mail, fazendo a validação antes do envio buscando o caractere "@".|
|---|```type="url"```|Input do tipo texto voltado para URL, fazendo a validação antes do envio, buscando palavras como "https://"|
|---|```type="date"```|Input do tipo data, permitindo a introdução de datas na caixa de diálogo.|
|---|```type="month"```|Input do tipo data, permitindo a introdução de datas por mês, na caixa de diálogo. *Vale-se notar que o Firefox não tem compatibilidade com o mesmo.*|
|---|```type="week"```|Input do tipo data, permitindo a introdução de datas por semana, na caixa de diálogo. *Vale-se notar que o Firefox não tem compatibilidade com o mesmo*.|
|---|```type="checkbox"```|Input do tipo caixa, adicionando caixa de seleções. Possui modificadores associados como: ```name=""``` para determinar o mesmo bloco.|
|---|```type="radio"```|Input do tipo botão rádio. Possui modificadores associados como: ```name=""``` para determinar o mesmo bloco.|

#### Modificador <input type="checkbox">

|Modificador Secundário|Função|
|---|---|
|```name=""```|Serve para indicar o ```id``` da caixa de seleção, fazendo com que agrupe os dados no mesmo contexto.|
|```name="$nomedavariavel[]"```|Transforma a variável em um ```array```, transformando em um lista, para melhor leitura via servidor.|
|```valor=""```|Adiciona o valor que será enviado do input.|
|```disabled```|Deixa o campo inativo.|

#### Tag <input type="radio">

|Modificador Secundário|Função|
|---|---|
|```name=""```|Serve para indicar o ```id``` da caixa de seleção, fazendo com que agrupe os dados no mesmo contexto.|
|```valor=""```|Adiciona o valor que será enviado do input.|
|```disabled```|Deixa o campo inativo.|

### Tag <button> e seus modificadores

|Tag|Modificador|Função|
|---|---|---|
|```<button>```|---|Adiciona o botão interativo.|
|```<button>```|```type=""```|Determina o tipo do botão.|
|---|```type="button"```|Botão do tipo padrão.|
|---|```type="reset"```|Apaga o conteúdo dos campos do formulário pai.|
|---|```type="submit"```|Envia o conteúdo do formulário pai.|

### Tag <select>, <option> e seus modificadores

|Tag|Modificador|Função|
|---|---|---|
|```<select>```|---|Adiciona uma caixa de seleção com menu suspenso.|
|```<select>```|```name=""```|Determina o nome do campo.|
|```<select>```|```multiple```|Permite que possa selecionar mais de um item na caixa de seleção.|
|```<option>```|---|Adiciona a opção para caixa de seleção do ```<select>```.|
|```<option>```|```value=""```|Valor que será enviado para o servidor.|
|```<option>```|```selected```| Transforma a opção em padrão para o menu seletor.|

### Tag <textarea> e seus modificadores

|Tag|Modificador|Função|
|---|---|---|
|```<textarea>```|---|Adiciona um campo de texto para maior número de caracteres.|
|```<textarea>```|```rows=""```|Determina a altura para o campo, baseado-se em linhas.|
|```<textarea>```|```cols=""```|Determina a largura para o campo, baseando-se em colunas.|

Created by [Gabu](https://www.github.com/gabrielbasto) 👾
