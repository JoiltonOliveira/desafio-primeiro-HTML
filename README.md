# A Criação do Universo - Desafio DIO HTML

## 📚 Sobre o Desafio

Este projeto foi desenvolvido como parte do **Desafio de Projeto da Formação HTML Web Developer da DIO.ME**. O objetivo é elaborar um website utilizando uma estrutura básica com as tags HTML aprendidas nas aulas práticas.

### Tema do Projeto
O website apresenta o relato da **Criação do Universo** baseado no livro de Gênesis, com uma narrativa que detalha os sete dias da criação, sua estrutura e organização.

---

## 🎯 Requisitos do Desafio

### ✅ Tags Obrigatórias Utilizadas

- **`<h1>` até `<h6>`**: Títulos e subtítulos em diferentes níveis hierárquicos
- **`<p>`**: Parágrafos de texto
- **`<mark>`**: Destaque de informações importantes
- **`<small>`**: Texto menor para informações adicionais
- **`<i>`**: Texto em itálico
- **`<u>`**: Texto sublinhado
- **`<strong>`**: Texto em negrito (forte ênfase semântica)
- **`<ol>`**: Listas ordenadas
- **`<ul>`**: Listas não ordenadas
- **`<li>`**: Itens de lista
- **`<a>`**: Links de navegação
- **`<hr>`**: Linhas horizontais para separação
- **`<sub>`**: Índices (ex: H₂O)
- **`<sup>`**: Expoentes (ex: 3 x 10⁵)
- **`<blockquote>`**: Citações em bloco

### 🆕 Tags Adicionais Exploradas

| Tag | Descrição | Exemplo |
|-----|-----------|---------|
| **`<font>`** | Define cor e estilo do texto | `<font color="blue">Título</font>` |
| **`<del>`** | Marca texto deletado/riscado | `<del>texto removido</del>` |
| **`<abbr>`** | Define abreviações com explicação | `<abbr title="baseado no livro genesis 1 & 2 do Adauto Lourenço">(em genesis 1 e 2)</abbr>` |

---

## 📁 Estrutura do Projeto

```
Nova pasta/
├── index.html              # Página principal - Relato da Criação
├── relacao-dias/
│   └── relacaodias.html   # Página de detalhes - Estrutura dos Dias
└── README.md               # Este arquivo
```

---

## 📄 Descrição das Páginas

### 🏠 `index.html` - Página Principal

**Conteúdo:** Relato completo da criação nos sete dias

- **Seção 1:** Introdução com o primeiro dia
- **Seções 2-7:** Detalhamento dos dias 2 a 7
- **Conclusão:** Reflexão final com citação bibliográfica

**Tags principais:**
- Títulos estruturados com `<h1>` e `<h2>`
- Parágrafos com formatação usando `<strong>`, `<i>`, e `<mark>`
- Links internos para a página complementar

### 📊 `relacao-dias/relacaodias.html` - Estrutura dos Dias

**Conteúdo:** Análise da organização estrutural da criação

- **Estrutura:** Apresenta a relação entre os dias
  - Dias 1-3: Formação dos ambientes
  - Dias 4-6: Preenchimento dos ambientes

**Tags principais:**
- Lista ordenada `<ol>` com sublistas `<ul>` aninhadas
- Uso de `<sup>` para velocidade da luz (3 x 10⁵ km/s)
- Fórmula química com `<sub>` (H₂O)
- Parágrafos estruturados com `<strong>`

---

## 💡 Exemplos de Tags Utilizadas

### Formatação de Texto
```html
<!-- Texto em negrito com ênfase -->
<strong>Deus</strong>

<!-- Texto destacado em amarelo -->
<mark>pela força da Sua palavra</mark>

<!-- Texto em itálico -->
<i>No princípio</i>

<!-- Texto pequeno para rodapé -->
<small>Assim (em genesis 1 e 2)...</small>

<!-- Abreviação com título -->
<abbr title="baseado no livro genesis 1 & 2 do Adauto Lourenço">(em genesis 1 e 2)</abbr>
```

### Semântica e Hierarquia
```html
<!-- Título principal -->
<h1>A Criação do Universo</h1>

<!-- Subtítulos -->
<h2>Relato da Criação</h2>
<h3>A relação costuma ser apresentada assim:</h3>

<!-- Separadores -->
<hr>
```

### Listas Complexas
```html
<ol>
    <li>Dia 1: luz e trevas
        <ul>
            <li>Dia 4: sol (3 x 10<sup>5</sup> km/s), lua e estrelas</li>
        </ul>
    </li>
    <li>Dia 2: céu e águas (H<sub>2</sub>O)
        <ul>
            <li>Dia 5: aves e peixes</li>
        </ul>
    </li>
</ol>
```

### Citação
```html
<blockquote>
    Genesis 1 e 2 Adauto Lourenço, <i>O Livro da Criação</i>, Editora Vida, 2018.
</blockquote>
```

### Links
```html
<a href="relacao-dias/relacaodias.html">Saiba mais...</a>
```

---

## 🎓 Aprendizados

Este desafio permitiu a prática de:

✨ **Semântica HTML:** Uso correto de tags para significado e acessibilidade  
✨ **Hierarquia:** Estrutura apropriada com títulos em diferentes níveis  
✨ **Formatação:** Diversos estilos de texto para melhor legibilidade  
✨ **Navegação:** Criação de links internos e estrutura multi-página  
✨ **Organização:** Estrutura bem definida com pastas e arquivos  
✨ **Documentação:** Abreviações e explicações usando `<abbr>`

---

## 📚 Referência Bibliográfica

- Genesis 1 e 2 (Bíblia Sagrada)
- Adauto Lourenço, *O Livro da Criação*, Editora Vida, 2018

---

## 👤 Autor

Desenvolvido como desafio da **Formação HTML Web Developer - DIO.ME**

---

## 📝 Notas

- O projeto utiliza UTF-8 como codificação
- Viewport configurado para responsividade
- Idioma definido como português brasileiro (pt-BR)
- A tag `<font>` foi utilizada para fins didáticos (em projetos reais, usar CSS é recomendado)

