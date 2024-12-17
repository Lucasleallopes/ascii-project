# Objeto ASCII 3D Giratório

Este projeto é uma aplicação web que exibe um objeto 3D giratório em ASCII. Os usuários podem interagir com o objeto usando vários controles para alterar sua forma, velocidade de rotação, direção e mais. A aplicação também suporta a importação de modelos 3D personalizados no formato STL.

## Funcionalidades

- **Renderização ASCII 3D**: Exibe objetos 3D usando caracteres ASCII.
- **Seleção de Forma**: Escolha entre uma esfera e um cubo.
- **Controle de Rotação**: Ajuste a velocidade e a direção da rotação.
- **Pausar/Retomar**: Pause e retome a animação.
- **Zoom e Arrastar**: Use o mouse para dar zoom e arrastar para rotacionar o objeto manualmente.
- **Modo Escuro/Claro**: Alterne entre temas escuro e claro.
- **Importação de STL**: Importe modelos 3D personalizados no formato STL.
- **Design Responsivo**: Adapta-se a diferentes tamanhos de tela.

## Uso

1. **Abrir a Aplicação**: Abra `index.html` em um navegador web.
2. **Controles**:
   - **Pausar/Retomar**: Use os botões "Pause" e "Resume" para controlar a animação.
   - **Direção**: Selecione a direção da rotação (Direita ou Esquerda) no menu suspenso.
   - **Forma**: Escolha a forma (Esfera ou Cubo) no menu suspenso.
   - **Velocidade**: Ajuste a velocidade de rotação usando o controle deslizante.
   - **Importar STL**: Clique em "Import STL" para carregar um modelo 3D personalizado.
   - **Resetar**: Clique em "Reset" para reverter para a forma e configurações iniciais.
   - **Modo Escuro/Claro**: Alterne o tema usando o botão "Dark/Light Mode".
3. **Interações com o Mouse**:
   - **Arrastar**: Clique e arraste na tela para rotacionar o objeto manualmente.
   - **Zoom**: Use a roda do mouse para dar zoom in e out.

## Detalhes Técnicos

- **Canvas HTML5**: Usado para renderizar os gráficos ASCII.
- **JavaScript**: Gerencia a animação, interações do usuário e análise de arquivos STL.
- **CSS**: Estiliza a aplicação e fornece design responsivo.

## Estrutura de Arquivos

- `index.html`: Arquivo HTML principal contendo a estrutura e lógica da aplicação.
- **Estilos**: Estilos CSS inline são usados para layout e design.
- **Scripts**: Código JavaScript está embutido no arquivo HTML para gerenciar a funcionalidade.

## Melhorias Futuras

- Adicionar mais formas e opções de personalização.
- Melhorar a análise de STL para modelos mais complexos.
- Melhorar o desempenho para animações mais suaves.

## Licença

Este projeto é de código aberto e está disponível sob a Licença MIT. Sinta-se à vontade para usar, modificar e distribuir conforme necessário.
