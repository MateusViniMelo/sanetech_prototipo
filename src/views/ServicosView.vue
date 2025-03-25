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
                                <h5 class="card-title">Revisão de Caixas d’Água e Orientação de Limpeza</h5>
                                <p class="card-text text-secondary">Visita técnica para revisar vazamentos, mau cheiro e
                                    orientar sobre limpeza e vedação correta da caixa d’água..</p>
                                <p class="fw-bold">R$ 90,00</p>

                            </div>
                        </div>

                    </div>
                    <div class="col-md-4 col-lg-6 col-xl-4 my-2">
                        <div class="card">
                            <img src="/images/manutencao_fossa.jpg" class="card-img-top" alt="...">
                            <div class="card-body">
                                <h5 class="card-title">Manutenção Econômica de Fossas Sépticas</h5>
                                <p class="card-text text-secondary">Serviço de manutenção de fossas com instrução básica
                                    de cuidado e prevenção de entupimentos e contaminação.</p>
                                <p class="fw-bold">R$ 180,00</p>

                            </div>
                        </div>

                    </div>
                    
                </div>
            </div>

        </div>
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped></style>