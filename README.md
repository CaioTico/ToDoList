# ToDoList
 
**Gerenciador de Tarefas**

Este é um simples aplicativo web para gerenciar tarefas, desenvolvido em PHP e HTML/CSS. Ele permite adicionar novas tarefas, listar as tarefas existentes e limpar a lista de tarefas.

### Como Usar

1. **Adicionar Tarefas:** No campo fornecido, insira o nome da nova tarefa que deseja adicionar e clique no botão "Cadastrar".

2. **Listar Tarefas:** As tarefas adicionadas serão listadas logo abaixo do formulário de adição.

3. **Limpar Tarefas:** Para limpar todas as tarefas da lista, clique no botão "Limpar Tarefas".

### Estrutura do Código

- **PHP (index.php):**
  - Inicializa a sessão.
  - Verifica se a sessão de tarefas existe e, se não existir, a inicializa como um array vazio.
  - Adiciona novas tarefas à sessão quando o parâmetro 'task_name' é recebido via método GET.
  - Limpa todas as tarefas da sessão quando o parâmetro 'clear' é recebido via método GET.

- **HTML/CSS (style.css):**
  - Define a estrutura visual do aplicativo, incluindo layout, estilos de formulários, lista de tarefas e botões.

### Captura de Tela

![Captura de Tela](./capa/Captura%20de%20tela%202024-04-29%20092605.png)

### Como Contribuir

1. Faça um fork deste repositório.
2. Clone o fork em sua máquina local.
3. Faça suas melhorias ou correções.
4. Commit suas alterações.
5. Envie um pull request.

### Autor

Este projeto foi desenvolvido por [@MonolitoPHP](https://github.com/MonolitoPHP).

---

**Nota:** Este aplicativo é uma implementação básica e pode ser expandido com mais recursos e melhorias. Sinta-se à vontade para contribuir e adicionar novos recursos conforme necessário.
