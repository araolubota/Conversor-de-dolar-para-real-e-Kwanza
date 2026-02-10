# Conversor de Dólar para Real e Kwanza

Um conversor de moeda simples e elegante que permite converter valores entre Dólar Americano (USD) e Real Brasileiro (BRL). Futuramente incluirá suporte para Kwanza Angolano (AOA).

##  Descrição

Este projeto é uma aplicação web desenvolvida para realizar conversões de moeda de forma rápida e intuitiva. A interface permite inserir valores em qualquer uma das moedas e ver a conversão em tempo real.

##  Funcionalidades

- Conversão de USD (Dólar Americano) para BRL (Real Brasileiro)
- Conversão de BRL (Real Brasileiro) para USD (Dólar Americano)
- Conversão em tempo real enquanto você digita
- Formatação automática de valores monetários
- Interface limpa e responsiva
- Design moderno com gradiente de cores

##  Tecnologias Utilizadas

- **HTML5** - Estrutura da página
- **CSS3** - Estilização e layout responsivo
- **JavaScript** - Lógica de conversão e interatividade

##  Como Usar

### Pré-requisitos

- Um navegador web moderno (Chrome, Firefox, Safari, Edge)

### Instalação

1. Clone este repositório:
```bash
git clone https://github.com/araolubota/Conversor-de-dolar-para-real-e-Kwanza.git
```

2. Navegue até o diretório do projeto:
```bash
cd Conversor-de-dolar-para-real-e-Kwanza
```

3. Abra o arquivo `index.html` no seu navegador web

Ou simplesmente faça o download do código e abra o arquivo `index.html` diretamente no navegador.

##  Como Funciona

1. Digite um valor no campo USD (Dólar) ou BRL (Real)
2. A conversão será feita automaticamente no outro campo
3. Os valores são formatados automaticamente quando você clica fora do campo

**Nota:** A taxa de câmbio atualmente está definida como R$ 5,10 por dólar. Para atualizar a taxa, modifique o valor da variável `dolar` no arquivo `assets/script.js`.

##  Estrutura do Projeto

```
Conversor-de-dolar-para-real-e-Kwanza/
│
├── index.html           # Página principal
├── assets/
│   ├── logo.png        # Logo do conversor
│   ├── script.js       # Lógica de conversão
│   ├── style.css       # Estilos da aplicação
│   └── estudar.js      # Arquivo de estudos/notas
└── README.md           # Este arquivo
```

##  Recursos de Design

- Interface com gradiente de cores (azul claro para branco)
- Campos de entrada com efeitos de foco
- Design responsivo que se adapta a diferentes tamanhos de tela
- Tipografia otimizada para legibilidade
- Sombras suaves para dar profundidade

##  Personalização

### Atualizar a Taxa de Câmbio

Edite o arquivo `assets/script.js` e altere o valor da variável `dolar`:

```javascript
let dolar = 5.1  // Altere este valor para a taxa atual
```

### Modificar Estilos

Os estilos podem ser personalizados no arquivo `assets/style.css`. As variáveis CSS estão definidas no início do arquivo:

```css
:root {
    --background: #FFF;
    --primary: #333333;
    --foreground: #e7f4c9;
    --secondary: #909090;
    --accent: #2563eb;
}
```

##  Autor

Desenvolvido por **Arão Lubota**

##  Licença

Este projeto está disponível para uso livre.

##  Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para:

1. Fazer um Fork do projeto
2. Criar uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Fazer commit das suas alterações (`git commit -m 'Adiciona MinhaFeature'`)
4. Fazer push para a branch (`git push origin feature/MinhaFeature`)
5. Abrir um Pull Request

##  Notas

- O arquivo `estudar.js` contém notas e exemplos de estudo sobre JavaScript e não é usado na aplicação principal
- O projeto menciona Kwanza no título, mas atualmente implementa apenas conversão entre USD e BRL. O suporte para Kwanza está planejado para versões futuras

##  Melhorias Futuras

- Adicionar conversão para Kwanza (AOA)
- Integração com API de taxas de câmbio em tempo real
- Adicionar mais moedas
- Histórico de conversões
- Modo escuro/claro
- Gráfico de variação das taxas


 Se este projeto foi útil para você, considere dar uma estrela no repositório!
