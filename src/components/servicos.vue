<template>
  <section id="servicos" class="text-center py-5 my-5">
    <div class="row pt-5 mt-5">
      <div class="col-12">
        <h2 class="fw-bold display-5">Serviços Prestados</h2>
      </div>
    </div>
    <div class="row mt-5">
      <div class="col-lg-4 mt-5">
        <img
          src="../assets/redes.png"
          class="rounded-circle border shadow p-5 icon"
          alt=""
        />

        <h2 class="fw-normal mt-3">Gestão de Redes Sociais</h2>
        <p>
          Esse serviço envolve a criação, curadoria e agendamento de conteúdo para plataformas como Facebook, Instagram, LinkedIn e Twitter. A agência monitora o desempenho das postagens, engajamento com o público e desenvolve estratégias para aumentar seguidores e interações.
        </p>
        <p><a class="btn btn-secondary" href="#">View details »</a></p>
      </div>
      <!-- /.col-lg-4 -->
      <div class="col-lg-4 mt-5">
        <img
          src="../assets/seo.png"
          class="rounded-circle border shadow p-5 icon"
          alt=""
        />

        <h2 class="fw-normal mt-3">SEO (Otimização para Mecanismos de Busca)</h2>
        <p>
          O SEO melhora a visibilidade de um site nos resultados de busca orgânica, otimizando o conteúdo e a estrutura do site. A agência usa palavras-chave relevantes, cria backlinks e ajusta o desempenho técnico do site para alcançar melhores posições no Google.
        </p>
        <p><a class="btn btn-secondary" href="#">View details »</a></p>
      </div>
      <!-- /.col-lg-4 -->
      <div class="col-lg-4 mt-5">
        <img
          src="../assets/marketing.png"
          class="rounded-circle border shadow p-5 icon"
          alt=""
        />

        <h2 class="fw-normal mt-3">Marketing de Conteúdo</h2>
        <p>
          Esse serviço inclui a criação de conteúdo relevante (posts de blog, vídeos, e-books) para atrair e engajar o público-alvo. O objetivo é educar e nutrir potenciais clientes, melhorando a autoridade da marca e incentivando conversões ao longo do tempo.
        </p>
        <p><a class="btn btn-secondary" href="#">View details »</a></p>
      </div>
      <!-- /.col-lg-4 -->
    </div>
  </section>
</template>
<script>
export default {
  name: "Servicos",
};
</script>
<style>
  .icon{
    max-width: 162px;
    max-height: 162px;
  }
</style>
