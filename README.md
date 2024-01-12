Input PT 1

Este é um exemplo simples de HTML que demonstra vários tipos de elementos <input> e como eles podem ser utilizados em formulários web.


Tipos de Input
Input com Autocompletar e Somente Leitura

<input autocomplete="street-address" readonly value="Alex Dyna">


Este input possui autocompletar para endereço de rua, é somente leitura e já contém o valor "Alex Dyna".


Input para Digitação de Dados

<input>


Input com Autocompletar para Endereço de Rua

<input autocomplete="street-address">

Usado por navegadores de internet para autocompletar informações de endereço.


Input Desabilitado

<input disabled>

Este input está desabilitado, impedindo a interação do usuário.


Input com Valor Preenchido

<input value="Alex Dyna">

Este input possui um valor pré-definido, que é "Alex Dyna".


Input Somente Leitura

<input readonly>

Este input é somente leitura, não permitindo a edição direta.


Input com Placeholder

<input placeholder="Digite sua rua">

Este input tem um espaço reservado (placeholder) que fornece uma dica sobre o que deve ser inserido.


Label Associado a um Input

<label>
    Rua:
    <input autocomplete="street-address">
</label>

O elemento <label> envolve o texto "Rua" e o <input>, associando-os.


Label com Apontamento por ID

<label for="rua">Rua</label>
<input id="rua">

O <label> possui um atributo for que aponta para o id do <input>, estabelecendo uma associação.

Input com Autofoco

<input autofocus>

Este input tem o foco automaticamente quando a página é carregada, permitindo a digitação imediata.

Sinta-se à vontade para utilizar este exemplo como referência para criar formulários mais complexos e personalizados em seus projetos.