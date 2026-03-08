# Registro de Bugs

## BUG01 - Sistema permite cadastrar curso com formulário vazio

**Severidade/Impacto:** Alta

**Passos para reproduzir:**

1. Acessar a aplicação  
   Link: https://creative-sherbet-a51eac.netlify.app/
2. Clicar na opção da barra superior "Cadastrar curso", localizada no lado direito da tela
3. Deixar todos os campos do formulário em branco
4. Clicar no botão "Cadastrar curso"

**Resultado atual:**
O sistema permitiu o cadastro do curso mesmo com todos os campos do formulário em branco. Após clicar em "Cadastrar curso", o sistema apresentou mensagem de sucesso e redirecionou para a listagem de cursos, exibindo um card sem informações preenchidas.

**Resultado esperado:**
O sistema deve impedir o cadastro do curso e apresentar validações informando que existem campos obrigatórios não preenchidos.

---

## BUG02 - Sistema exibe mensagem de exclusão com sucesso, mas não remove o curso da listagem

**Severidade/Impacto:** Alta

**Passos para reproduzir:**

1. Acessar a aplicação
   Link: https://creative-sherbet-a51eac.netlify.app/
2. Clicar na opção da barra superior "Listar cursos", localizada no lado direito da tela
3. Identificar um curso existente na listagem
4. Clicar no botão "Excluir curso" do card
5. Observar a mensagem exibida e verificar a listagem
6. Atualizar a página
7. Verificar novamente a listagem

**Resultado atual:**
O sistema exibe mensagem de exclusão com sucesso, porém o curso permanece visível na listagem mesmo após atualizar a página.

**Resultado esperado:**
Após a exclusão com sucesso, o curso deve ser removido da listagem e não voltar a aparecer após a atualização da página.

---

## BUG03 - Descrição longa quebra a proporção do card na listagem de cursos

**Severidade/Impacto:** Baixa

**Passos para reproduzir:**

1. Acessar a aplicação
   Link: https://creative-sherbet-a51eac.netlify.app/
2. Clicar na opção da barra superior "Cadastrar curso", localizada no lado direito da tela
3. Preencher os campos do formulário com dados válidos
4. Localizar o campo "Descrição do curso"
5. Inserir uma descrição longa (ex: 500 caracteres)
    Utilizar o site: https://loremipsum.io
6. Cadastrar o curso
7. Acessar a listagem de cursos

**Resultado atual:**
O card da listagem exibe toda a descrição inserida, tornando o card muito alto e desproporcional em relação aos demais elementos da interface.

**Resultado esperado:**
A listagem deveria tratar descrições longas, exibindo apenas um resumo ou limitando o texto visível no card para manter consistência visual na interface.

---

## BUG04 - Campo "Tipo de curso" permite selecionar a opção "Selecione..." após seleção prévia

**Severidade/Impacto:** Baixa

**Passos para reproduzir:**

1. Acessar a aplicação
    Link: https://creative-sherbet-a51eac.netlify.app/
2. Clicar na opção "Cadastrar curso", localizada no canto superior direito da tela
3. Localizar o campo "Tipo de curso"
4. Selecionar uma opção válida no campo, como "Online" ou "Presencial"
5. Abrir novamente o dropdown do campo "Tipo de curso"
6. Tentar selecionar a opção "Selecione..."

**Resultado atual:**
Após selecionar uma opção válida no campo "Tipo de curso", o sistema permitiu selecionar a opção "Selecione".

**Resultado esperado:**
A opção "Selecione..." deve funcionar apenas como texto orientativo inicial do campo, não devendo aparecer como uma opção válida para seleção pelo usuário em nenhum momento.
