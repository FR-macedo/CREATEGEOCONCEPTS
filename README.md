## Dudaaaa
## lê isso aqui:

### mudanças sugeridas

1. reaorganizar os arquivos em pastas distintas de acordo com o tipo e a função de cada um 

coloquei as imagens em uma pasta separada, a logo está em uma pasta chamada "public" porque ela vai ser usada diversas vezes e por várias páginas
(depois de realizar a alteração do local das imagens, vai ser necessário mudar a forma como elas são refenciadas no html de cada página, se uma arquivo antes  era refenciado por "duda.png" atualmente ele será "./public/duda.png")

```
/meu-projeto
    /public
        duda.png
        1.png
        2.png
        ...
    /styles
        index.css
    /pages
        inicio.html
        conceitos.html
        exercicios.html
        blog.html
    /scripts
        script-global.js
    index.html
    README.md
```

2. mudei o nome dos arquivos que compõem o index(a pagina principal da apliacação), assim fica clara a função deles

3. também seria bom renomear o arquivo das imagens e usar o atributo (alt="")[https://inovalize.com.br/atributo-alt-o-que-e-e-por-que-voce-deve-usar-em-seu-site/], dessa forma fica claro o uso de cada arquivo sem precisar ler o codigo

4. você pode separar as seções da página em outras páginas, deixando a navegabilidade mais linmpa, deixei um exemplo dentro da pasta pages. Separei os items do header e coloquei cada um em uma pagina 

5. a tag <img> não precisa de tag de fechamento

6. deixei o script comentado dentro das novas paginas que criei porque tu aintençãoe era fazer um scroll suave dentro da mesma pagina, como eu criei varia paginas, removi essa função

