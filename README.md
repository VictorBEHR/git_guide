<html>
  <head><h1><strong>git_guide</strong></h1></head>
  <body>
    <div>
      <p>Este é o guia com os comandos do git que mais utilizo no dia a dia</p>
      <ul>
    </div>
    <div>
      <ul>
        <li>
          <p>git branch</p>
          <p>Lista as branchs da máquina(com asterisco é a que estou)</p>
        <li>
          <p>git diff</p>
          <p>Mostra a diferenteça entre a commit atual e a anterior</p>
        </li>
          <li>
            <p>git revert (codigo identificador da commit)</p>
            <p>Reverte para a commit do codigo, não salvando
        </li>
        <li>
          <p>git stash</p>
          <p>Joga fora tudo o que NAO foi add</p>
    </div>
    <div>
      <ul>
        <li>
          <p>ctrl+shift+v</p>
          <p>Para melhor visualização do arquivo HTML no VSCode</p>
        </li>
      </ul>
    </div>
    <div>
      <ul>
        <li>
          <p>git init</p>
          <p>Comando para inicializar um repositório git no diretório em questão</p>
        </li>
        <li>
          <p>git log</p>
          <p>Comando para exibir um log de todos os commits realizados</p>
          <p>Cada commit tem um identificador único</p>
        </li>
        <li>
          <p>git status</p>
          <p>Comando para verificar e exibir se há alguma pendência que ainda não está sendo rastreada pelo git. Por exemplo, um novo arquivo ou um arquivo modificado. 
          Para resolver isso, deve-se utilizar o comando git add para adicionar as mudanças e então o comando git status retornará que não há nada pendente.</p>
        </li>
        <li>
          <p>git add</p>
          <p>Comando para adicionar um arquivo que não está sendo rastreado pelo git.</p>
          <ul>Parâmetros<li>-A : adiciona todos os arquivos modificados de uma única vez</li></ul>
        </li>
        <li>
          <p>git commit</p>
          <p>Comando para criar um snapshot do diretório onde o git foi iniciado. Assim, caso qualquer imprevisto aconteça, é possível retornar ao estado anterior.</p>
          <ul>Parâmetros<li>-m : Permite inserir uma mensagem entre aspas duplas para dar clareza ao que foi feito no commit</li></ul>
        </li>
        <li>
          <p>git rebase</p>
          <p>Comando para adicionar um arquivo que não está sendo rastreado pelo git.</p>
          <ul>Parâmetros
            <li>-i : modo iterativo, útil para unir vários commits em um só</li>
            <li>[branch]~n : nome da branch, seguido do número de commit que deseja unir. Em seguida é exibido um arquivo de texto onde deve-se mudar o parâmetro "pick" dos commits para "squash", deixando apenas o commit mais antigo com "pick". Em seguida, será pedido para definir a mensagem utilizada nessa união de commits.</li>
          </ul>
          <p>Exemplo: git rebase -i master~3 (faz a união dos 3 últimos commits em master)</p>
        </li>
        <li>
          <p>git clone</p>
          <p>Comando para clonar um repositório git no diretório em questão.</p>
          <ul>Parâmetros
            <li>link : link do repositório que se deseja clonar</li>            
          </ul>
          <p>Exemplo: git clone https://gitbuh.com/VitorAlho/git_guide</p>
        </li>
        <li>
          <p>git remote</p>
          <p>Comando para criar/deletar/consultar os repositórios cadastrados para backup em nuvem do projeto.</p>
          <p>git remote: mostra os repositórios remotos</p>
          <ul>Parâmetros
            <li>add : adiciona um novo repositório. Exemplo: git remote add origin</li>  
            <li>remove : remove um repositório. Exemplo: git remote remove origin</li>
          </ul>
        </li>
        <li>
          <p>git push</p>
          <p>Comando para enviar todas as novas alterações em branches para o repositório na nuvem</p>
            <ul>
              <li>git push origin main</li>
                <ul><li>origin: Para onde</li>
                <li>main: branch (neste caso, principal)</li>
            </ul>
            </ul>
        </li>
        <li>
          <p>git pull</p>
          <p>Comando para atualizar o repositório local com as novas alterações do repositório na nuvem.</p>
          <p>Pode-se selecionar a branch:</p>
            <ul><li>
            git pull main
            </li>
            </ul>
        </li>
        <li>
          <p>git reset</p>
          <p>Comando para retornar à um commit anterior, desfazendo ou não tudo o que foi feito.</p>
          <ul>Parâmetros
            <li>--hard : desfaz tudo o que foi feito e apaga todos os commits posteriores ao commit escolhido</li>             
          </ul>
        </li>
      </ul>
    </div>
  </body>
</html>
