# CSS Styling Methods

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css&logoColor=white)

Projeto didático que apresenta **três versões de uma mesma página de perfil**, cada uma utilizando uma forma diferente de aplicar CSS.

## Sobre o projeto

As páginas apresentam imagem de perfil circular, nome e links de GitHub, Facebook e Instagram, com uma aparência visual equivalente. A comparação evidencia como a organização do CSS muda sem alterar a proposta da interface.

## Implementações

| Técnica | Aplicação dos estilos |
| --- | --- |
| **CSS inline** | Diretamente nos atributos `style` dos elementos. |
| **CSS interno** | Em um bloco `<style>` dentro do HTML. |
| **CSS externo** | No arquivo `style.css`, vinculado com `<link>`. |

## Estrutura

```text
css-styling-methods/
├── Inline/
│   ├── index.html
│   └── Minha_foto.png
├── Interno/
│   ├── index.html
│   └── Minha_foto.png
├── Externo/
│   ├── index.html
│   ├── style.css
│   └── Minha_foto.png
└── README.md
```

## Tecnologias utilizadas

- HTML5.
- CSS3.

## Conceitos praticados

- Atributo `style`, bloco `<style>` e vínculo por `<link>`.
- Seletores e reutilização de estilos.
- `text-align`, `background-color`, `border-radius` e `width`.
- `display: block`, margens e preenchimento em links.
- Organização de recursos locais.

## Como executar

1. Clone ou baixe o repositório.
2. Abra o `index.html` de cada pasta no navegador.
3. Compare o resultado e a localização das regras de estilo.

## Observações

Os links para GitHub, Facebook e Instagram usam `href="#"` e ainda são **demonstrativos**, sem redirecionamento aos perfis reais. A versão `Inline/index.html` também pode receber a estrutura completa de um documento HTML em uma revisão futura.

## Objetivo

Comparar CSS inline, interno e externo e entender os efeitos dessas abordagens na organização e manutenção do código.
