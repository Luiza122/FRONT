### README: Projeto "Energia Limpa"

---

## **Descrição do Projeto**
O site "Energia Limpa" é um projeto web informativo sobre fontes de energia renovável e sustentável. Ele foi desenvolvido com o objetivo de conscientizar as pessoas sobre os benefícios das energias limpas e fornecer conteúdo educacional por meio de textos, imagens, e vídeos.

---

## **Funcionalidades**
- **Seção de Sobre**: Explica o conceito de energia limpa e sua importância.
- **Benefícios**: Destaca os principais benefícios das fontes de energia sustentável.
- **Tipos de Energia**: Apresenta informações sobre energia solar, eólica, hidráulica, entre outras, com cards interativos.
- **Vídeos Educativos**: Inclui um carrossel com vídeos que explicam as principais fontes de energia limpa.
- **Formulário de Contato**: Permite que os usuários enviem dúvidas ou sugestões.
- **Design Responsivo**: O layout se adapta a diferentes tamanhos de tela, garantindo uma boa experiência em dispositivos móveis.

---

## **Tecnologias Utilizadas**
- **HTML5**: Estrutura semântica do site.
- **CSS3**: Estilização do site, incluindo gradientes e responsividade.
- **Bootstrap 5**: Framework CSS para facilitar o design responsivo e componentes pré-formatados.
- **Font Awesome**: Para ícones sociais e estéticos.
- **JavaScript**: Para interatividade no carrossel de vídeos.

---

## **Como Usar**
1. Clone o repositório ou baixe o arquivo `.zip` do projeto.
2. Certifique-se de que a imagem `energia-limpa.jpg` está na mesma pasta do arquivo HTML.
3. Abra o arquivo `index.html` em um navegador para visualizar o site.

---

## **Estrutura de Arquivos**
```
/energia-limpa
│
├── index.html          # Arquivo principal do site
├── styles.css          # Estilização personalizada do site
├── energia-limpa.jpg   # Imagem de fundo do cabeçalho
├── energiasolar.jpg    # Imagem do card sobre energia solar
├── energiaeolica.jpg   # Imagem do card sobre energia eólica
├── energiahidraulica.jpg # Imagem do card sobre energia hidráulica
├── videos              # Pasta contendo links embutidos do YouTube
└── assets              # Outros arquivos de suporte (se aplicável)
```

---

## **Seções do Site**
### 1. **Cabeçalho**
- Imagem de fundo: `energia-limpa.jpg`.
- Título e subtítulo explicando o propósito do site.

### 2. **Navegação**
- Menu fixo no topo do site com links para seções importantes: Sobre, Benefícios, Tipos, Vídeos, e Contato.

### 3. **Conteúdo Principal**
- **Sobre**: Apresentação do tema.
- **Benefícios**: Lista com vantagens da energia renovável.
- **Tipos de Energia**: Cards interativos com imagens e descrições.
- **Vídeos Educativos**: Carrossel com vídeos do YouTube.
- **Contato**: Formulário simples para mensagens dos usuários.

### 4. **Rodapé**
- Informações de copyright.
- Links rápidos para navegação adicional.
- Ícones de redes sociais.

---

## **Como Personalizar**
1. **Trocar a Imagem do Cabeçalho**:
   - Substitua `energia-limpa.jpg` por uma imagem de sua escolha.
   - Atualize o caminho no CSS ou HTML.

2. **Alterar o Tema de Cores**:
   - Edite as variáveis CSS no arquivo `styles.css`:
     ```css
     :root {
       --primary-color: #007bff;
       --light-gray: #f8f9fa;
       --dark-gray: #343a40;
       --gradient-bg: linear-gradient(135deg, #2d6187, #a3d9ff);
     }
     ```

3. **Adicionar Mais Tipos de Energia**:
   - Insira novos `<div class="card">` na seção **Tipos de Energia**, com as respectivas imagens e descrições.

---

## **Preview**
![Screenshot do Site](energia-limpa-preview.jpg) *(Substitua por um screenshot do site em execução.)*

---

## **Requisitos**
- Um navegador moderno, como Google Chrome, Firefox ou Edge.
- Conexão com a internet para carregar vídeos do YouTube.

---

## **Autor**
Desenvolvido por **[Seu Nome]**.  
Entre em contato pelo email: **seuemail@exemplo.com**  

---

## **Licença**
Este projeto está licenciado sob a licença MIT. Sinta-se à vontade para usar e modificar conforme necessário.