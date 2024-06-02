# ProjetoLP
<h1>Trabalho Unity - Desenvolvimento de Cena</h1>
<h3></h3>
<h2>
  A finalidade da cena é simular uma quadra de basquete, onde carros passam na rua atrás da quadra, 
e uma bola de basquete cai da cesta e quica. Já para implementação futuras de movimento irá se criar
um personagem jogador de basquete que pode se mover na quadra se interagindo com a bola de basquete.
  O desenvolvimento primeiro se compôs na criação do cenário, utilizando as ferramentas oferecidas,
como a utilização da asset store e a criação de objetos como quadrados e esferas para composição de
objetos mais complexos, após isso, foi inserido a textura e o objeto da bola de basquete. Logo foi
trabalhado os elementos da física, como o rigbody e sphere collider.
</h2> 

<p>
<img src="https://github.com/lipeoo/ProjetoLP/assets/162318706/8d1c16fd-a843-4d0b-a6ea-41b2f0c6eaaf">
<h2>5 objetos:</h2>
  <li>Bola de Basquete</li>
  <li>Cesta de basquete</li>
  <li>Grade</li>
  <li>Terreno</li>
  <li>Quadra</li>
</p>.
<p>
  <h3>Texturas</h3>
<h2>
    As texturas servem para se incrementar nos objetos, necessária para para que um objeto tenha uma
  cor, e como seu próprio nome diz, um textura diferente. Podendo-se aplicar uma imagem a objetos.
</h2>
  <img src="https://github.com/lipeoo/ProjetoLP/assets/162318706/38291745-9187-4680-b83c-84dacb2efd40">
  <h2>
    A utilização de textura foi para a bola de basquete parece-se uma bola de verdade,
  porém a falta de uma biblioteca para texturas específicas torna o aprimoramento inviável. Tornando 
  na maioria das vezes a preferência de se evitar usar textura em alguns materias, por isso apenas
  por enquanto foi utilizado apenas na bola de basquete.
  </h2>
<img src="https://github.com/lipeoo/ProjetoLP/assets/162318706/d7ec32fb-e89b-43a3-af50-6adec6404320">
</p>
<p>
  <h3>Asset Store</h3>
  <h2>
      A asset store serve como uma loja onde podemos comprar, desde de pagos à gratuitos, assets(objetos,
    sons,texturas,efeitos,etc...). A utilização da asset store foi para compor o cenário da cena, que se
    passa em uma cidade.  
  </h2>
![image](https://github.com/lipeoo/ProjetoLP/assets/162318706/2221ed7a-3f32-4b77-9548-eb0dec228a88)
</p>
<p>
<h3>Física</h3>
<h2>
    A física no Unity necessita que se crie um asset de física, onde se pode editar a fricção e as 
  quicadas(bounce). 
</h2>
![image](https://github.com/lipeoo/ProjetoLP/assets/162318706/946d0fc5-2ead-4016-990a-5f06dac1d3af)
  <h2>
    Então se deve ter um objeto que tenha um colisor, como box collider, sphere collider, terrain collider,
  etc... e deve aplicar o asset de física criado nesse collider, que então provê diferentes características.
  No entanto é necessário adicionar a colisão Rigbody que não deforma o corpo em que foi aplicado e permite
  retirar gravidade, colocar massa e entre outras características.
  Exemplo física da bola de basquete:
</h2>
![image](https://github.com/lipeoo/ProjetoLP/assets/162318706/33271687-df69-4590-a09f-239605664f56)
</p>
