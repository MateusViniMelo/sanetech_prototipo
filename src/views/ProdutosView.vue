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
                            <img src="/images/estacao_compacta_residencial.webp" class="img-fluid object-fit-cover"
                                alt="...">
                            <div class="card-body">
                                <h5 class="card-title link " data-bs-toggle="modal" data-bs-target="#staticBackdrop">
                                    Mini Estação Compacta de Tratamento de Esgoto (Residencial)</h5>
                                <p class="card-text text-secondary">Sistema modular de fácil instalação para residências
                                    ou pequenas
                                    propriedades. Dispensa rede de esgoto.</p>
                                <p class="fw-bold">R$ 2.900,00</p>

                            </div>
                        </div>

                    </div>
                    <div class="col-md-4 col-lg-6 col-xl-4 my-2">
                        <div class="card">
                            <img src="/images/filtro_uv.png" class="card-img-top" alt="...">
                            <div class="card-body">
                                <h5 class="card-title link " data-bs-toggle="modal" data-bs-target="#staticBackdrop">
                                    Sistema UV de Purificação de Água</h5>
                                <p class="card-text text-secondary">Purificador com lâmpada UV para eliminação de
                                    bactérias e vírus em água potável..</p>
                                <p class="fw-bold">R$ 1.200,00</p>

                            </div>
                        </div>

                    </div>
                    <div class="col-md-4 col-lg-6 col-xl-4 my-2">
                        <div class="card">
                            <img src="/images/filtro_areia.webp" class="card-img-top" alt="...">
                            <div class="card-body">
                                <h5 class="card-title link " data-bs-toggle="modal" data-bs-target="#staticBackdrop">Kit
                                    de Filtro de Areia Lento para Água Potável (Familiar)</h5>
                                <p class="card-text text-secondary">Sistema de filtragem de baixo custo para residências
                                    e pequenas comunidades. Utiliza camadas de areia, cascalho e carvão ativado para
                                    remover impurezas, tornando a água segura para consumo doméstico.</p>
                                <p class="fw-bold">R$ 480,00</p>

                            </div>
                        </div>

                    </div>
                    <div class="col-md-4 col-lg-6 col-xl-4 my-2">
                        <div class="card">
                            <img src="/images/kit_captacao_agua.webp" class="card-img-top" alt="...">
                            <div class="card-body">
                                <h5 class="card-title link " data-bs-toggle="modal" data-bs-target="#staticBackdrop">Kit
                                    de Captação de Água da Chuva (1.000 litros)</h5>
                                <p class="card-text text-secondary">Conjunto com calha, filtro, bomba manual e
                                    reservatório plástico para áreas urbanas.</p>
                                <p class="fw-bold">R$ 850,00</p>

                            </div>
                        </div>

                    </div>
                    <div class="col-md-4 col-lg-6 col-xl-4 my-2">
                        <div class="card">
                            <img src="/images/cisterna.jpg" class="card-img-top" alt="...">
                            <div class="card-body">
                                <h5 class="card-title link " data-bs-toggle="modal" data-bs-target="#staticBackdrop">
                                    Cisterna Modular de Polietileno (30.000 litros)</h5>
                                <p class="card-text text-secondary"> Ideal para escolas, sítios e comunidades. Material
                                    resistente e de fácil transporte.</p>
                                <p class="fw-bold">R$ 2.500,00</p>

                            </div>
                        </div>

                    </div>
                    <div class="col-md-4 col-lg-6 col-xl-4 my-2">
                        <div class="card">
                            <img src="/images/biodigestor.jpg" class="card-img-top" alt="...">
                            <div class="card-body">
                                <h5 class="card-title link " data-bs-toggle="modal" data-bs-target="#staticBackdrop">
                                    Biodigestor Doméstico para Resíduos Orgânicos</h5>
                                <p class="card-text text-secondary">Transforma restos de comida e esterco em biogás e
                                    fertilizante líquido.</p>
                                <p class="fw-bold">R$ 3.800,00</p>

                            </div>
                        </div>

                    </div>
                    <div class="col-md-4 col-lg-6 col-xl-4 my-2">
                        <div class="card">
                            <img src="/images/coposta.jpg" class="card-img-top" alt="...">
                            <div class="card-body">
                                <h5 class="card-title link " data-bs-toggle="modal" data-bs-target="#staticBackdrop">
                                    Composteira Caseira de 3 Níveis</h5>
                                <p class="card-text text-secondary"> Estrutura empilhável para compostagem doméstica com
                                    minhocas (vermicompostagem).</p>
                                <p class="fw-bold">R$ 250,00</p>

                            </div>
                        </div>

                    </div>
                    <div class="col-md-4 col-lg-6 col-xl-4 my-2">
                        <div class="card">
                            <img src="/images/kit_jardim_chuva.png" class="card-img-top" alt="...">
                            <div class="card-body">
                                <h5 class="card-title link " data-bs-toggle="modal" data-bs-target="#staticBackdrop">Kit
                                    Jardim de Chuva (1m²)</h5>
                                <p class="card-text text-secondary"> Inclui substrato, manta geotêxtil e plantas nativas
                                    para captação natural da água da chuva.</p>
                                <p class="fw-bold">R$ 320,00</p>

                            </div>
                        </div>

                    </div>
                    <div class="col-md-4 col-lg-6 col-xl-4 my-2">
                        <div class="card">
                            <img src="/images/kit_permeavel.jpg" class="card-img-top" alt="...">
                            <div class="card-body">
                                <h5 class="card-title link " data-bs-toggle="modal" data-bs-target="#staticBackdrop">
                                    Piso Permeável de Concreto (m²))</h5>
                                <p class="card-text text-secondary">Blocos vazados que permitem infiltração da água no
                                    solo, evitando alagamentos.</p>
                                <p class="fw-bold">R$ 120,00</p>

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
                        <h1 class="modal-title fs-5" id="staticBackdropLabel">Compra de produto</h1>
                        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                    </div>
                    <div class="modal-body">
                        Você deseja comprar o produto?
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


.link {
    cursor: pointer;
}

.link:hover {
    color: #06B6D4;
}
</style>