# 🎲 Sorteio de Números

[![GitHub Pages](https://img.shields.io/badge/🌐-Site%20Online-blue?style=for-the-badge)](https://leandrostanger.github.io/SorteioDeNumeros/)
[![GitHub](https://img.shields.io/badge/📂-Repositório-black?style=for-the-badge)](https://github.com/LeandroStanger/SorteioDeNumeros)

Uma aplicação web simples e interativa para realizar sorteios aleatórios de números dentro de um intervalo definido pelo usuário.

## 📝 Descrição

O **Sorteio de Números** é uma ferramenta web que permite ao usuário definir um valor máximo e, com um clique, gerar um número aleatório entre 1 e o valor escolhido. Ideal para sorteios rápidos, brincadeiras, tomada de decisões ou para entender conceitos básicos de geração de números aleatórios em JavaScript.

## 🚀 Acesso Online

Teste a aplicação diretamente no seu navegador:  
**[https://leandrostanger.github.io/SorteioDeNumeros/](https://leandrostanger.github.io/SorteioDeNumeros/)**

## 🚀 Tecnologias Utilizadas

O projeto foi desenvolvido com tecnologias web padrão, sem dependências externas:

- **HTML5**: Estrutura da página e elementos de interface.
- **CSS3**: Estilização visual, layout e responsividade.
- **JavaScript (ES6+)**: Lógica para capturar o valor máximo, gerar o número aleatório e exibir o resultado.

## 📂 Estrutura do Projeto

A estrutura é minimalista e contém todos os arquivos na raiz:

```
SorteioDeNumeros/
├── index.html          # Página principal com formulário e resultado
├── style.css           # Estilos visuais da aplicação
├── script.js           # Lógica do sorteio e interatividade
└── README.md           # Documentação
```

## ⚙️ Funcionalidades

Com base na interface disponível, as funcionalidades implementadas são:

1. **Definição do Intervalo**: O usuário insere o valor máximo (ex.: 100) para o sorteio.
2. **Sorteio Aleatório**: Ao clicar no botão "Sortear", um número inteiro aleatório entre 1 e o valor máximo é gerado.
3. **Exibição do Resultado**: O número sorteado é mostrado imediatamente na tela.
4. **Validação Básica**: O sistema provavelmente verifica se o valor máximo é um número válido (positivo).
5. **Design Responsivo**: A interface se adapta a diferentes tamanhos de tela.

## 🔧 Como Executar o Projeto

### Pré-requisitos

- Navegador web moderno (Chrome, Firefox, Edge, Safari)
- Editor de código (opcional, para modificar)

### Passo a Passo

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/LeandroStanger/SorteioDeNumeros.git
   cd SorteioDeNumeros
   ```

2. **Abra o arquivo `index.html`** diretamente no navegador:
   - Dê um duplo clique no arquivo
   - Ou arraste-o para uma janela do navegador

3. **Utilize a aplicação**:
   - Digite um número máximo no campo indicado
   - Clique no botão "Sortear"
   - Veja o número sorteado aparecer na tela

## 🎯 Exemplo de Uso

| Campo | Ação | Resultado |
|-------|------|-----------|
| Número máximo = 50 | Clicar em "Sortear" | Exibe um número aleatório entre 1 e 50 |
| Número máximo = 10 | Clicar em "Sortear" | Exibe um número aleatório entre 1 e 10 |

## 🔧 Personalização

Se desejar modificar o projeto:

- **Aparência**: Edite o arquivo `style.css` para alterar cores, fontes e layout.
- **Comportamento**: Modifique o `script.js` para adicionar validações extras, sorteio com intervalo mínimo ou outros formatos de resultado.

## 🌐 Configurações Importantes

- O projeto é totalmente estático, não requer servidor back-end.
- Funciona perfeitamente hospedado em **GitHub Pages**.

## 👤 Autor

**Leandro Stanger**

- GitHub: [@LeandroStanger](https://github.com/LeandroStanger)
- Projeto: [Sorteio de Números](https://github.com/LeandroStanger/SorteioDeNumeros)
- Demonstração Online: [https://leandrostanger.github.io/SorteioDeNumeros/](https://leandrostanger.github.io/SorteioDeNumeros/)
