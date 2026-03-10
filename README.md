🍔 Bom Appetit Emanuel - Site de Hamburgueria
Site profissional e responsivo para hamburgueria, desenvolvido em HTML, CSS e JavaScript puro em um único arquivo. Permite que os clientes visualizem o cardápio, montem pedidos com adicionais e finalizem via WhatsApp.

📱 Funcionalidades
🛒 Carrinho de Compras
Adicionar/remover produtos

Alterar quantidades

Cálculo automático de total

Persistência com localStorage

Carrinho flutuante com resumo

🧩 Sistema de Adicionais
Disponível para Kit Solteiro e Kit Casal

Limite de 4 itens por kit

Itens em destaque com descrição detalhada

Modal exclusivo para seleção

📋 Fluxo de Pedido em 4 Etapas
Carrinho - Revisão dos itens

Dados - Nome e telefone

Endereço - Local de entrega

Opções - Agendamento, comentários, pagamento

💬 Finalização via WhatsApp
Mensagem formatada automaticamente

Inclui todos os dados do pedido

Adicionais descritos

Número do pedido único

🖼️ Visualização de Imagens
Clique nas fotos para ampliar

Modal otimizado para celular

⏰ Status da Loja
Indica se está aberto (18h às 00h)

Atualização automática

🛠️ Tecnologias Utilizadas
HTML5 - Estrutura semântica

CSS3 - Design responsivo (mobile-first)

JavaScript - Toda lógica e interatividade

LocalStorage - Persistência do carrinho

WhatsApp API - Envio de pedidos

📦 Estrutura de Arquivos
text
bomappetit/
├── index.html          # Site completo (único arquivo)
├── img/                # Pasta de imagens
│   ├── logo-bom-appetit.png
│   ├── favicon.ico
│   ├── favicon-96x96.png
│   ├── favicon.svg
│   ├── apple-touch-icon.png
│   ├── site.webmanifest
│   └── ... (demais fotos dos produtos)

🎨 Design

Cores: Fundo escuro (#111111) com detalhes em laranja (#ff4d1c)

Tipografia: Fonte Inter (moderna e legível)

Botões: Grandes e táteis para celular

Cards: Produtos em destaque com sombras

Responsivo: Adaptado para todos os tamanhos de tela

🚀 Como Usar
Clone o repositório:

bash
git clone https://github.com/drezjn/bomappetitemanuel.git
Adicione suas imagens na pasta img/

Configure o número do WhatsApp:

Localize 5531991591673 no código

Substitua pelo número da sua loja

Faça o deploy no GitHub Pages ou qualquer hospedagem

🔧 Personalização
Adicionar novos produtos:
No JavaScript, localize a lista produtos e adicione:

javascript
{ id: 'novoId', nome: 'Produto', desc: 'Descrição', preco: 00.00, img: 'img/produto.png', cat: 'categoria' }
Criar novo produto com adicionais:
javascript
{ 
    id: 'novoId', 
    nome: 'Produto', 
    preco: 00.00, 
    img: 'img/produto.png', 
    cat: 'categoria',
    temAdicionais: true,
    limiteAdicionais: 4,
    adicionais: [
        { nome: 'Item extra', preco: 5.00 }
    ] 
}
Categorias disponíveis:
promocoes - Promoções especiais

hamburgueres - Hambúrgueres artesanais

combos - Kits e combos

porcoes - Porções e petiscos

bebidas - Refrigerantes

sucos - Sucos Del Valle

📱 Compatibilidade
✅ Celulares: Android e iOS

✅ Tablets: Todos os tamanhos

✅ Desktop: Navegadores modernos

✅ WhatsApp: Integração direta

⚡ Performance
Código único e otimizado

Imagens comprimidas

Carregamento rápido em 3G/4G

Scroll suave nativo

🐛 Solução de Problemas
Favicon não aparece no GitHub:
Adicione ./ antes do caminho:

html
<link rel="icon" href="./img/favicon.ico">
Imagens não carregam:
Verifique se a pasta img/ está na raiz e os nomes dos arquivos correspondem exatamente.

Carrinho não persiste:
O localStorage funciona apenas no mesmo domínio. Verifique se não está em modo anônimo.

📄 Licença
Este projeto é de uso comercial livre para o Bom Appetit Emanuel.

👨‍💻 Desenvolvedor
Desenvolvido sob demanda para Bom Appetit Emanuel com foco em usabilidade mobile e conversão via WhatsApp.

