# Criando um projeto em VueJS com VueCLI 

## VueJS
Vue.js é um framework JAVASCRIPT progressivo de código aberto, que funciona na camada de visualização da aplicação. Ele trabalha juntamente com as tecnologias HTML E CSS, que são utilizadas para desenvolvimento de aplicações web.
<br>
<br>
## VueCLI
Vue CLI é uma ferramenta de linha de comando feita pela comunidade do Vue para facilitar ainda mais a inicialização de uma nova aplicação Vue, com ela podemos gerar nossa aplicação a partir de templates oficiais, diminuindo o tempo de configuração de ambiente.
<br>
<br>
## Instalação

Para  instalar globalmente do vue  na sua máquina execute o seguinte comando no terminal:

<code>npm install -g @vue/cli
</code> 

*OBS: Lembrando que para instalar é necessário ter instalado o node.js e o npm em sua máquina.*
<br>
<br>
Após a instalação, você terá acesso ao vuebinário em sua linha de comando. Você pode verificar se ele está instalado corretamente simplesmente executando vue, que apresentará uma mensagem de ajuda listando todos os comandos disponíveis.

Após a instalação execute o seguinte comando para verificar a versão do vue instalada!


<code>vue --version
</code>

## Iniciado um projeto com VueCLI
Para criar o primeiro projeto com vue basta rodar o seguinte comando: 


<code>vue create helloWorld</code>  

Ao executar esse comando, surgirá algumas opções para configurar o projeto. Escolha a configuração padrão.
O proximo passo executar a aplicação. Para isso , teremos que entrar dentro do diretorio onde o comando para criação foi executado e executar o seguinte comando:

<code>npm run serve
</code>

Depois que o projeto carregar, precisamos ir até o navegador para vizualizar sua estrura inicial,por padrão a aplicação vai rodar nesse endereço: **http://localhost:8080**

Pronto se tudo tiver certo você abrirá uma página com uma logo do vuejs no centro!

