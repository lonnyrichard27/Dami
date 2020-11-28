<template>
<footer class="bg">
<div class="container footerpadding text-white">
    <div class="d-flex bd-highlight">
        <div class="p-2 w-100 bd-highlight">
            <h1>MR DAHUNSI</h1>
        </div>
        <div class="p-2 flex-shrink-1 bd-highlight">
            <div class="d-flex">
                <article class="icons">
                    <a href="#" target="_blank" class="fa fa-facebook fa-1x text-center" style="color:white" title="facebook" rel="noopener"></a>
                </article>
                <article class="icons ml-2">
                    <a href="#" target="_blank" class="fa fa-twitter fa-1x" title="twitter" style="color:white" rel="noopener"></a>
                </article>
                <article class="icons ml-2">
                    <a href="#" target="_blank" class="fa fa-google-plus fa-1x" title="google-plus" rel="noopener" style="color:white"></a>
                </article>
                <article class="icons ml-2">
                    <a href="#" target="_blank" class="fa fa-linkedin fa-1x" title="linkedin" style="color:white" rel="noopener"></a>
                </article>
                <article class="icons ml-2">
                    <a href="#" target="_blank" class="fa fa-pinterest fa-1x" title="pinterest" style="color:white"  rel="noopener"></a>
                </article>
                <article class="icons ml-2">
                    <a href="#" target="_blank" class="fa fa-skype fa-1x" title="skype" style="color:white" rel="noopener"></a>
                </article>
            </div>
        </div>
    </div>
    <hr class="line mt-5 mb-5" />
    <div class="row">
        <div class="col-lg-3 col-md-6 col-sm-12">
            <h3 class="font-weight-bolder">About software</h3>
            <article class="smallline mt-4 mb-4"></article>
            <p class="text-muted">Vivamus lectus ligula, consectetur in <br /> ligula sit amet, mollis aliquet sapien. <br />Donec egestas leo nec velit porta,<br /> eu sodales eros auctor.</p>

            <p class="text-muted">Pellentesque placerat urna eu iaculis<br /> dictum. Donec bibendum pellentesq<br /> risus,commodo dapibus eros maxim<br /> quis.Curabitur at finibus nulla.</p>
        </div>
        <div class="col-lg-3 col-md-6 col-sm-12">
            <h3>Our Services</h3>
            <article class="smallline  mt-4 mb-4"></article>
            <a href="#" class="chevright text-decoration-none text-muted">Vivamus</a><br />
            <a href="#" class="chevright text-decoration-none text-muted">Vivamus</a><br />
            <a href="#" class="chevright text-decoration-none text-muted">Vivamus</a><br />
            <a href="#" class="chevright text-decoration-none text-muted">Vivamus</a><br />
            <a href="#" class="chevright text-decoration-none text-muted">Vivamus</a><br />
            <a href="#" class="chevright text-decoration-none text-muted">Vivamus</a><br />
            <a href="#" class="chevright text-decoration-none text-muted">Vivamus</a>
        </div>
        <div class="col-lg-3 col-md-6 col-sm-12">
            <h3>Quick Links</h3>
            <article class="smallline  mt-4 mb-4"></article>
            <a href="#" class="chevright text-decoration-none text-muted">Vivamus</a><br />
            <a href="#" class="chevright text-decoration-none text-muted">Vivamus</a><br />
            <a href="#" class="chevright text-decoration-none text-muted">Vivamus</a><br />
            <a href="#" class="chevright text-decoration-none text-muted">Vivamus</a><br />
            <a href="#" class="chevright text-decoration-none text-muted">Vivamus</a><br />
            <a href="#" class="chevright text-decoration-none text-muted">Vivamus</a><br />
            <a href="#" class="chevright text-decoration-none text-muted">Vivamus</a>
        </div>
        <div class="col-lg-3 col-md-6 col-sm-12">
            <h3>Contact Info</h3>
            <article class="smallline"></article>
            <p class="text-muted">
                Street 238,52 tempor<br />
                Donec ultricies mattis nulla, suscipit<br /> risus tristique utmattis nulla.
            </p>
            <article class="mt-4">
                <p class="text-muted">Phone: 1.800.555.6789</p>
                <p class="text-muted">E-mail:info@sktthemes.org</p>
                <p class="text-muted">Website:https://sktthemes.org</p>
            </article>
        </div>
    </div>
    <hr class="line mt-5 mb-5" />
    <div class="d-flex bd-highlight">
        <div class="p-2 w-100 bd-highlight">
            <p class="text-muted">© 2020 SKT Software Pro. All Rights Reserved.</p>
        </div>
        <div class="p-2 flex-shrink-1 bd-highlight">
            <p class="text-muted">Designed by SKT.</p>
        </div>
    </div>
</div>
</footer>
</template>

<script>
export default {
        
}
</script>

<style scoped>
article.smallline {
    background-color: #5629b7;
    width: 21%;
    height: 1%;
}
.chevright::before{
    content: "\f105";
    font-family: FontAwesome;
    font-size: 17px;
    padding-right: 10px;
}
article.icons {
    height: 45px;
    background-color: black;
    width: 45px;
    text-align: center;
    border-radius: 50%;
    padding-top: 10px;
}
.footerpadding{
    padding-top: 12rem;
}
.bg{
    height: 868px;
    background: url('../assets/footer.svg')
}
hr.line {
    background-color: gray;
}
</style>