<template>
  <div class="hello">

    <!-- Responsive navbar-->
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
            <div class="container px-5">
                <a class="navbar-brand" href="#!">Portofolio</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation"><span class="navbar-toggler-icon"></span></button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
                        <li class="nav-item"><a class="nav-link active" aria-current="page" href="#!">Home</a></li>
                        <li class="nav-item"><a class="nav-link" href="#!">About</a></li>
                        <li class="nav-item"><a class="nav-link" href="#!">Contact</a></li>
                    </ul>
                </div>
            </div>
        </nav>
        <!-- Page Content-->
        <div class="container px-4 px-lg-5">
            <!-- Heading Row-->
            <div class="row gx-4 gx-lg-5 align-items-center my-5">
                <div class="col-lg-7"><img class="img-fluid rounded mb-4 mb-lg-0" src= foto.jpeg alt="..." /></div>
                <div class="col-lg-5">
                    <h1 class="font-weight-light">Biography</h1>
                    <p>Nama saya adalah Sinshevan Viswanatan Kravizt Erwi. Saya lahir di Palembang pada tanggal 3 September 2003. Saya bertempat tinggal di Jln. Parameswara No. 24 RT. 01. Saya memiliki hobi bermain game dan membaca komik. </p>
                </div>
            </div>
            <!-- Content Row-->
            <div class="row gx-4 gx-lg-5">
                <div class="col-md-4 mb-5">
                    <div class="card h-100">
                        <div class="card-body">
                            <h2 class="card-title">Pendidikan</h2>
                            <p class="card-text">2007-2009 di TK Xaverius 4, 2009-2015 di SD Xaverius 4, 2015-2017 di SMP Xaverius Maria, 2017-2020 di SMA Xaverius 1, 2020-sekarang kuliah di Universitas MDP</p>
                        </div>
                        <div class="card-footer"><a class="btn btn-primary btn-sm" href="#!">More Info</a></div>
                    </div>
                </div>
                <div class="col-md-4 mb-5">
                    <div class="card h-100">
                        <div class="card-body">
                            <h2 class="card-title">No. Telepon atau WhatsApp</h2>
                            <p class="card-text">087769926334</p>
                        </div>
                        <div class="card-footer"><a class="btn btn-primary btn-sm" href="#!">More Info</a></div>
                    </div>
                </div>
                <div class="col-md-4 mb-5">
                    <div class="card h-100">
                        <div class="card-body">
                            <h2 class="card-title">Email</h2>
                            <p class="card-text">Email = erwisin@mhs.mdp.ac.id atau erwisin123@gmail.com
                            </p>
                        </div>
                        <div class="card-footer"><a class="btn btn-primary btn-sm" href="#!">More Info</a></div>
                    </div>
                </div>
            </div>
        </div>
        <!-- Footer-->
        <footer class="py-5 bg-dark">
            <div class="container px-4 px-lg-5"><p class="m-0 text-center text-white">Copyright &copy; Your Website 2021</p></div>
        </footer>
    </div>
 
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>
