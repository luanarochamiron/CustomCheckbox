# Custom Checkbox Design - Toggle Switch On/Off

Um componente de interface de utilizador (UI) interativo, moderno e responsivo focado na estilização de botões de alternância (Toggle Switches) utilizando exclusivamente HTML5 e CSS3. O projeto substitui a caixa de seleção padrão do navegador por um interruptor deslizante fluido e elegante, ideal para páginas de configurações ou alternância de modos (como Light/Dark Mode).

## Tecnologias Utilizadas

* HTML5: Estruturação semântica utilizando elementos do tipo checkbox (`<input type="checkbox">`) e suas respectivas etiquetas vinculadas (`<label>`).
* CSS3: Estilização completa, uso de bordas totalmente arredondadas, sombras internas/externas e gerenciamento de estados.
* Animações em CSS: Aplicação de transições suaves (`transition`) e transformações (`transform: translateX`) para o movimento deslizante do interruptor.

## Funcionalidades e Técnicas Aplicadas

* Customização de Checkbox Nativo: Ocultação do seletor padrão do navegador, transferindo toda a interatividade e o design visual para o elemento irmão customizado por meio do seletor `:checked`.
* Interruptor Deslizante Fluido (Smooth Toggle): Uso de pseudo-elementos (`::before` ou `::after`) para renderizar a esfera interna flutuante, que desliza de forma responsiva ao alternar os estados de ativado e desativado.
* Feedback de Estado Textual: Exibição inline do status correspondente (exibindo "Disabled" ou "Enabled") posicionado simetricamente ao lado do interruptor.
* Efeito Neumórfico e Sombras Discretas: Uso de gradientes suaves e `box-shadow` na esfera e no trilho do botão para conferir profundidade e um aspecto tridimensional tátil.
* Layout de Alto Contraste: Centralização absoluta do card branco com CSS Flexbox sobre um plano de fundo roxo plano e vibrante, gerando foco visual imediato.

## Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone 
