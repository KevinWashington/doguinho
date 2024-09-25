<template>
  <section id="faq" class="py-5 my-5">
    <div class="row mt-5 pt-5">
      <div class="col-12 text-center">
        <h2 class="display-5 fw-bold">Perguntas Frequentes</h2>
      </div>
    </div>
    <div class="row mt-3 mb-5">
      <div class="col-12">
        <div class="accordion" id="accordionExample">
          <div class="accordion-item">
            <h2 class="accordion-header" id="headingOne">
              <button
                class="accordion-button bg-light"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#collapseOne"
                aria-expanded="true"
                aria-controls="collapseOne"
              >
              <strong>COMO FUNCIONA?</strong>
              
              </button>
            </h2>
            <div
              id="collapseOne"
              class="accordion-collapse collapse show"
              aria-labelledby="headingOne"
              data-bs-parent="#accordionExample"
            >
              <div class="accordion-body bg-light">
                O cliente entra em contato com a nossa empresa e informa que tipo de divulgação ele(a) quer, depois o cliente vai participar de uma reunião com nossos funcionários para que seja possível entender como será feita e administrada essa divulgação. Por último, tudo será colocado em prática.
              </div>
            </div>
          </div>
          <div class="accordion-item">
            <h2 class="accordion-header" id="headingTwo">
              <button
                class="accordion-button collapsed bg-light"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#collapseTwo"
                aria-expanded="false"
                aria-controls="collapseTwo"
              >
              <strong>PÚBLICO-ALVO</strong>
              
              </button>
            </h2>
            <div
              id="collapseTwo"
              class="accordion-collapse collapse"
              aria-labelledby="headingTwo"
              data-bs-parent="#accordionExample"
            >
              <div class="accordion-body bg-light">
                Nosso público-alvo são pessoas que buscam praticidade na hora de promover o seu negócio, como: Empresas, Pessoas públicas, Empreendedores, Agências, Consultorias e entre outros...
              </div>
            </div>
          </div>
          <div class="accordion-item">
            <h2 class="accordion-header" id="headingThree">
              <button
                class="accordion-button collapsed bg-light"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#collapseThree"
                aria-expanded="false"
                aria-controls="collapseThree"
              >
                <strong>COMO FUNCIONA O PROCESSO DE CRIAÇÃO DE UMA ESTRATÉGIA DE MARKETING?</strong>
              </button>
            </h2>
            <div
              id="collapseThree"
              class="accordion-collapse collapse"
              aria-labelledby="headingThree"
              data-bs-parent="#accordionExample"
            >
              <div class="accordion-body bg-light">
                <p>Nosso processo é personalizado para atender às necessidades de cada cliente, mas geralmente seguimos os seguintes passos:</p>
    <ol>
      <li><strong>Diagnóstico inicial:</strong> Fazemos uma reunião para entender o seu negócio, o público-alvo e os objetivos da sua empresa.</li>
      <li><strong>Pesquisa de mercado:</strong> Realizamos uma análise detalhada do seu mercado e dos concorrentes para identificar oportunidades e desafios.</li>
      <li><strong>Definição de estratégia:</strong> Com base nos dados coletados, desenvolvemos uma estratégia de marketing personalizada, com táticas que podem incluir SEO, marketing de conteúdo, campanhas pagas, entre outras.</li>
      <li><strong>Execução:</strong> Nossa equipe coloca o plano em ação, monitorando o desempenho de cada etapa.</li>
      <li><strong>Análise e otimização:</strong> Mensalmente, entregamos relatórios detalhados sobre o progresso das campanhas e fazemos ajustes conforme necessário para maximizar os resultados.</li>
    </ol>
    <p>Este processo é flexível e pode ser ajustado conforme as demandas e os resultados que forem surgindo.</p>

              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name: "Faq",
};
</script>
<style>
  body.bg-dark .accordion-item, .accordion-button{
    color: #fff !important;
  }
  
</style>
