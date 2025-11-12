## Projeto - Landing Page para Barbearia/Barbeiro (HTML, CSS e JavaScript)

Este projeto consiste na implementação de uma **Landing Page completa e responsiva** para o barbeiro **Luiz Felipe**, focada na apresentação de serviços, diferenciais, avaliações de clientes e informações de contato. A página utiliza um design moderno com esquema de cores em tons de preto, branco e o destaque **Vintage Dourado (#AA8B56)**.

### 🚀 Sobre o Projeto

O objetivo é criar uma presença online profissional para o barbeiro, incentivando o agendamento e a interação. A navegação é facilitada por um menu *off-canvas* (hambúrguer) que se sobrepõe ao conteúdo.

### 🛠️ Tecnologias e Funcionalidades

| Tecnologia | Conceito / Uso |
| :--- | :--- |
| **HTML5** | Estrutura semântica das seções (`<section>`, `<div>`) e integração de *assets* (imagens, fontes, ícones). |
| **CSS3** | Estilização completa, uso de `(Flexbox)` para alinhamento e layouts responsivos, e efeitos de transição (como o *hover* nos botões e serviços). |
| **Responsividade (Media Queries)** | A página é totalmente adaptável para dispositivos móveis (`max-width: 770px`), ajustando tamanhos de fonte, layouts de coluna e a exibição do menu. |
| **Menu *Off-Canvas*** | Navegação lateral (`#sideNav`) que se esconde fora da tela e é revelada com um clique no botão de menu (`#menuBtn`) usando JavaScript. |
| **JavaScript** | Controle do estado do menu lateral (abrir/fechar) manipulando a propriedade `right` do CSS. |
| **Font Awesome** | Utilização de ícones para diferenciais (`#feature`), informações de contato (`#footer`) e redes sociais. |
| **Design Visual** | Esquema de cores: O tom `#AA8B56` (Vintage Dourado/Marrom) é usado como cor principal de destaque e fundo em diversas seções. |

### 📂 Estrutura do Projeto

O projeto é organizado nas seguintes seções:

1.  **Banner (`#banner`):** Seção de introdução com o logotipo, título do barbeiro (**"Luiz Felipe Cortes"**) e um botão de ação com efeito *hover*.
2.  **Menu de Navegação (`#sideNav`):** Menu *hambúrguer* lateral com links âncora para as seções principais.
3.  **Diferenciais (`#feature`):** Apresenta os pontos fortes do serviço (Profissionais Experientes, Reserva Online, Custo Acessível).
4.  **Serviços (`#service`):** Galeria visual com quatro serviços principais (Corte de Cabelo, Barba, Penteados, Lavagem), utilizando *overlays* para exibir a descrição ao passar o mouse.
5.  **Avaliações (`#testimonial`):** Apresenta depoimentos de clientes com imagens, nomes e ícones do Twitter.
6.  **Rodapé/Contato (`#footer`):** Informações de horário de funcionamento, endereço, e-mail e telefone, além de links para redes sociais.

### ⚙️ Como Executar

1.  Clone este repositório.
2.  Certifique-se de que a estrutura de arquivos (principalmente as pastas `css/`, `js/` e `img/`) está correta.
3.  Abra o arquivo `index.html` em seu navegador web (Google Chrome, Firefox, etc.).
