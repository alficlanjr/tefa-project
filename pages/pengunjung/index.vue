<template>
    <div class="container-fluid">
        <div class="row">
           <div class="col-lg-12">
             <h2 class="text-center my-4">RIWAYAT KUNJUNGAN</h2>
             <div class="my-3">
                <input type="search" class="form-control form-control-lg rounded-5" placeholder="Filter...">
             </div>
             <div class="my-3 text-muted">menampilkan 1 dari 1</div>
             <table class="table">
                <thead>
                    <tr>
                        <td>#</td>
                        <td>NAMA</td>
                        <td>KEANGGOTAAN</td>
                        <td>WAKTU</td>
                        <td>KEPERLUAN</td>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>1.</td>
                        <td>Alfi</td>
                        <td>Murid</td>
                        <td>27 pebruari 2024</td>
                        <td>Baca</td>
                    </tr>
                </tbody>
             </table>
           </div> 
    </div>
    <div class="d-flex justify-content-between">
        <nuxt-link to="/" class="btn btn-primary btn-lg rounded-5 px-5">
                        back
        </nuxt-link>
    </div>
    </div>
</template>