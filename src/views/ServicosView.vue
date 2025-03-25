<template>
    <div class="container-fluid justify-content-center">
        <div class="row justify-content-center">
            <div class="col-md-6 col-lg-4 col-xl-2 mb-5">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title mb-4">Pesquisa</h5>
                        <div class="form-floating mb-3">
                            <input type="email" class="form-control" id="floatingInput" placeholder="name@example.com">
                            <label for="floatingInput">Nome do Serviço</label>
                        </div>
                        <div class="form-floating">
                            <select class="form-select" id="floatingSelect" aria-label="Floating label select example">
                                <option selected>Todos</option>
                                <option value="1">Tratamento de Água e Esgoto</option>
                                <option value="2">Captação de Água da Chuva</option>
                                <option value="3">Biodigestores e Compostagem</option>
                                <option value="3">Drenagem Sustentável e Infraestrutura Verde</option>
                            </select>
                            <label for="floatingSelect">Tipos de Serviço</label>
                        </div>

                        <div class="mt-4 text-center">
                            <a class="btn btn-primary text-center" href="#" role="button"> <i class="bi bi-search"></i>
                                Pesquisar</a>
                        </div>

                    </div>
                </div>
            </div>
            <div class="col-12 col-lg-6">
                <div class="row ">
                    <div class="col-md-4 col-lg-6 col-xl-4 my-2">
                        <div class="card">
                            <img src="/images/limpeza_caixa.jpeg" class="img-fluid object-fit-cover" alt="...">
                            <div class="card-body">
                                <h5 class="card-title link ">
                                    Revisão de Caixas d’Água e Orientação de Limpeza</h5>
                                <p class="card-text text-secondary">Visita técnica para revisar vazamentos, mau cheiro e
                                    orientar sobre limpeza e vedação correta da caixa d’água..</p>
                                <p class="fw-bold ">R$ 90,00</p>
                                <div class="mt-3 text-end">
                                    <button type="button" class="btn btn-primary btn-sm" data-bs-toggle="modal"
                                        data-bs-target="#staticBackdrop">Comprar</button>
                                </div>

                            </div>
                        </div>

                    </div>
                    <div class="col-md-4 col-lg-6 col-xl-4 my-2">
                        <div class="card">
                            <img src="/images/manutencao_fossa.jpg" class="card-img-top" alt="...">
                            <div class="card-body">
                                <h5 class="card-title link ">
                                    Manutenção Econômica de Fossas Sépticas</h5>
                                <p class="card-text text-secondary">Serviço de manutenção de fossas com instrução básica
                                    de cuidado e prevenção de entupimentos e contaminação.</p>
                                <p class="fw-bold">R$ 180,00</p>
                                <div class="mt-3 text-end">
                                    <button type="button" class="btn btn-primary btn-sm" data-bs-toggle="modal"
                                        data-bs-target="#staticBackdrop">Comprar</button>
                                </div>
                            </div>
                        </div>

                    </div>
                    <div class="col-md-4 col-lg-6 col-xl-4 my-2">
                        <div class="card">
                            <img src="/images/teste_agua.jpg" class="card-img-top" alt="...">
                            <div class="card-body">
                                <h5 class="card-title link ">
                                    Teste Rápido da Qualidade da Água</h5>
                                <p class="card-text text-secondary">Avaliação simples da potabilidade da água de poços
                                    ou caixas d’água. Ideal para quem desconfia da água, mas não pode pagar laboratório.
                                </p>
                                <p class="fw-bold">R$ 60,00</p>
                                <div class="mt-3 text-end">
                                    <button type="button" class="btn btn-primary btn-sm" data-bs-toggle="modal"
                                        data-bs-target="#staticBackdrop">Comprar</button>
                                </div>
                            </div>
                        </div>

                    </div>

                    <div class="col-md-4 col-lg-6 col-xl-4 my-2">
                        <div class="card">
                            <img src="/images/instalacao_calha.jpg" class="card-img-top" alt="...">
                            <div class="card-body">
                                <h5 class="card-title link ">
                                    Instalação de Calhas para Captação de Água da Chuva</h5>
                                <p class="card-text text-secondary">Instalação de calhas e conduítes que redirecionam a
                                    água da chuva para bombonas ou cisternas reaproveitadas.
                                </p>
                                <p class="fw-bold">R$ 150,00</p>
                                <div class="mt-3 text-end">
                                    <button type="button" class="btn btn-primary btn-sm" data-bs-toggle="modal"
                                        data-bs-target="#staticBackdrop">Comprar</button>
                                </div>
                            </div>
                        </div>

                    </div>

                    <div class="col-md-4 col-lg-6 col-xl-4 my-2">
                        <div class="card">
                            <img src="/images/compostagem_comunitaria.webp" class="card-img-top" alt="...">
                            <div class="card-body">
                                <h5 class="card-title link ">
                                    Implantação de Compostagem Comunitária</h5>
                                <p class="card-text text-secondary">Montagem de composteiras em centros comunitários,
                                    escolas ou associações com orientação e manutenção inicial.
                                </p>
                                <p class="fw-bold">R$ 700,00</p>
                                <div class="mt-3 text-end">
                                    <button type="button" class="btn btn-primary btn-sm" data-bs-toggle="modal"
                                        data-bs-target="#staticBackdrop">Comprar</button>
                                </div>
                            </div>
                        </div>

                    </div>
                    <div class="col-md-4 col-lg-6 col-xl-4 my-2">
                        <div class="card">
                            <img src="/images/reaproveitar_agua_ar_condicionado.jpg" class="card-img-top" alt="...">
                            <div class="card-body">
                                <h5 class="card-title link ">
                                    Reaproveitamento de Água do Ar-Condicionado</h5>
                                <p class="card-text text-secondary">Instalação de mangueira e direcionamento da água
                                    condensada para baldes ou jardins — ideal para regiões quentes.
                                </p>
                                <p class="fw-bold">R$ 70,00</p>
                                <div class="mt-3 text-end">
                                    <button type="button" class="btn btn-primary btn-sm" data-bs-toggle="modal"
                                        data-bs-target="#staticBackdrop">Comprar</button>
                                </div>
                            </div>
                        </div>

                    </div>

                </div>
            </div>

        </div>
        <div class="modal fade" id="staticBackdrop" data-bs-backdrop="static" data-bs-keyboard="false" tabindex="-1"
            aria-labelledby="staticBackdropLabel" aria-hidden="true">
            <div class="modal-dialog">
                <div class="modal-content">
                    <div class="modal-header">
                        <h1 class="modal-title fs-5" id="staticBackdropLabel">Compra de serviço</h1>
                        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                    </div>
                    <div class="modal-body">
                        Você deseja comprar o serviço?
                    </div>
                    <div class="modal-footer">
                        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Cancelar</button>
                        <button type="button" class="btn btn-success">Sim</button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>

</script>

<style scoped>

</style>