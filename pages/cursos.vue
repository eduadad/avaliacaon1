<template>
  <div>
    
    <section class="hero is-white mb-5">
      <div class="hero-body">
        <p class="title">Cursos</p>
        <p class="subtitle">Escolha dentre os 4 cursos de cada categoria </p>
      </div>
    </section>

    <section>
      <div class="box">
 

      <b-tabs>
      
        <b-tab-item label ="Violão"> <h1 class="title">Aprenda com melhores professores de violão do Brasil</h1>
          
          <h2 class="subtitle">Os cursos vão dos mais iniciantes para os mais avançados com uma variedade de preços e todos na promoção </h2>
          <div class="columns">
  <div class="column">
    <router-link :to="{ path: '/curso1' }"><b-image class="image"  :src="require('@/assets/curso1.jpg')"></b-image></router-link>
    
    <h4 class="title is-4">Do zero ao fingerstyle</h4>
    <h4 class="subtitle is-4">Leandro Latú</h4>
    <b-rate custom-text="5"></b-rate>
    <strong><del>R$120,00</del></strong> R$100,00
  </div>
  <div class="column">
    <b-image class="image"  :src="require('@/assets/curso2.jpg')"></b-image>
    <h4 class="title is-4">Curso de harmonia</h4>
    <h4 class="subtitle is-4">Fabiano Chagas</h4>
    <b-rate custom-text="4,4"></b-rate>
    <strong><del>R$200,00</del></strong> R$150,00
  </div>
  <div class="column">
    <b-image class="image"  :src="require('@/assets/curso3.jpg')"></b-image>
    <h4 class="title is-4">Tocá de ouvido</h4>
    <h4 class="subtitle is-4">Nicholas Kiyuna</h4>
    <b-rate custom-text="4,7"></b-rate>
    <strong><del>R$300,00</del></strong> R$220,00
  </div>
  <div class="column">
    <b-image class="image"  :src="require('@/assets/curso4.jpg')"></b-image>
    <h4 class="title is-4">Top master violão básico</h4>
    <h4 class="subtitle is-4">Marco Bertaglia</h4>
    <b-rate custom-text="3"></b-rate>
    <strong><del>R$150,00</del></strong> R$130,00
  </div>
</div>


<br>
<br>

        </b-tab-item>

        <b-tab-item label="Teclado">
          Lorem <br />
          ipsum <br />
          dolor <br />
          sit <br />
          amet.
        </b-tab-item>
      </b-tabs>
      
    </div>
    </section>
    <h1 class="title">Mais vistos</h1>
<div class="columns">
  <div class="column">
    <b-image class="image"  :src="require('@/assets/curso5.jpg')"></b-image>
    <h4 class="title is-4">Curso de violão método tríade</h4>
    <h4 class="subtitle is-4">Leandro Latú</h4>
    <b-rate custom-text="5"></b-rate>
    <strong><del>R$120,00</del></strong> R$100,00
  </div>
  <div class="column">
    <b-image class="image"  :src="require('@/assets/curso6.jpg')"></b-image>
    <h4 class="title is-4">Fórmula do violão</h4>
    <h4 class="subtitle is-4">Fabiano Chagas</h4>
    <b-rate custom-text="4,4"></b-rate>
    <strong><del>R$200,00</del></strong> R$150,00
  </div>
  <div class="column">
    <b-image class="image"  :src="require('@/assets/curso7.jpg')"></b-image>
    <h4 class="title is-4">Aprenda violão desafio 10 dias</h4>
    <h4 class="subtitle is-4">Nicholas Kiyuna</h4>
    <b-rate custom-text="4,7"></b-rate>
    <strong><del>R$300,00</del></strong> R$220,00
  </div>
  
</div>
    

  </div>
  
  
</template>

