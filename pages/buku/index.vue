<template>
    <div class="container-fluid">
        <div class="row">
            <div class="col-lg-12">
                <h2 class="text-center my-4">BUKU</h2>
                <div class="my-3">
                   <input type="search" class="form-control rounded-5" placeholder="Mau baca apa hari ini?"> 
                </div>
                <div class="my-3 text-muted">menampilkan 8 dari 8</div>
                <div class="row">
                    <div class="col-lg-2">
                        <div class="card mb-3">
                            <div class="card-body">
                                <img src="~/assets/img/buku1.jpeg" class="buku" alt="buku 1">
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-2">
                        <div class="card mb-3">
                            <div class="card-body">
                                <img src="~/assets/img/buku2.jpg"  class="buku" alt="buku 2">
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-2">
                        <div class="card mb-3">
                            <div class="card-body">
                                <img src="~/assets/img/buku3.jpg"  class="buku" alt="buku 3">
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-2">
                        <div class="card mb-3">
                            <div class="card-body">
                                <img src="~/assets/img/buku4.jpg"  class="buku" alt="buku 4">
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-2">
                        <div class="card mb-3">
                            <div class="card-body">
                                <img src="~/assets/img/buku5.jpg"  class="buku" alt="buku 5">
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-2">
                        <div class="card mb-3">
                            <div class="card-body">
                                <img src="~/assets/img/buku6.jpg"  class="buku" alt="buku 6">
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-2">
                        <div class="card mb-3">
                            <div class="card-body">
                                <img src="~/assets/img/buku7.jpg"  class="buku" alt="buku 7">
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-2">
                        <div class="card mb-3">
                            <div class="card-body">
                                <img src="~/assets/img/buku8.jpg"  class="buku" alt="buku 8">
                            </div>
                        </div>
                    </div>
                </div>
            </div>
         </div>
     </div>
     <div class="d-flex justify-content-between">
        <nuxt-link to="/" class="btn btn-primary btn-lg rounded-5 px-5">
                        back
        </nuxt-link>
    </div>
</template>

<style scoped>
.card-body {
    width: 100%;
    height: 20em;
    padding: 0;
}
.buku {
    width: 100%;
    height: 100%;
    object-fit: buku;
    object-position: 0 30;
}
</style>