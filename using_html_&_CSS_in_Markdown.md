# formatando imagens 

## usando `</div>` 

Markdown não permite formatações de estilo, mas podemos usar html e css para complementar
vejamos a usabilidade de outras linguagens em markdown para criar alguns estilos.

**formatar alinhamento**
    `<div>`
      
    ![gato 1](imagens/istockphoto-1344022890-612x612.jpg 'gato 1')
    
    ![gato 2](imagens/istockphoto-1344022890-612x612.jpg 'gato 2')
    
    ![gato 3](imagens/istockphoto-1344022890-612x612.jpg 'gato 3')
    
    </div>

Também podemos ajustar a sua formatação

    <div style="display:flex;gap:10px>
      
    ![gato 1](imagens/istockphoto-1344022890-612x612.jpg 'gato 1')
    
    ![gato 2](imagens/istockphoto-1344022890-612x612.jpg 'gato 2')
    
    ![gato 3](imagens/istockphoto-1344022890-612x612.jpg 'gato 3')
    
    </div>

**usando `<style>`

<div>
      
![gato 1](imagens/istockphoto-1344022890-612x612.jpg 'gato 1')
    
![gato 2](imagens/istockphoto-1344022890-612x612.jpg 'gato 2')
    
![gato 3](imagens/istockphoto-1344022890-612x612.jpg 'gato 3')
    
</div>
<style>
img {max-width:200px;}
</style>

**Também podemos usar codifo de html para formatar as páginas de markdown**
