// Função para selecionar automaticamente o produto no formulário ao clicar no card
function selecionarProduto(nomeProduto) {
  const selectProduto = document.getElementById('produto-interesse');
  const secaoContato = document.getElementById('contato');

  if (selectProduto) {
    selectProduto.value = nomeProduto;
  }

  if (secaoContato) {
    secaoContato.scrollIntoView({ behavior: 'smooth' });
  }
}

// Manipulação do Formulário ao carregar a página
document.addEventListener('DOMContentLoaded', () => {
  const formulario = document.getElementById('form-prevenda');
  const mensagemSucesso = document.getElementById('mensagem-sucesso');

  formulario.addEventListener('submit', (event) => {
    event.preventDefault(); // Evita recarregar a página

    const nome = document.getElementById('nome').value;
    const email = document.getElementById('email').value;
    const produto = document.getElementById('produto-interesse').value;

    if (nome && email && produto) {
      // Oculta formulário e mostra mensagem de sucesso
      formulario.style.display = 'none';
      mensagemSucesso.classList.remove('hidden');
    }
  });
});
