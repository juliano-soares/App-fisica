<template>
    <div id="naoexcluir">
        <div class="row no-gutter">
            <div class="d-none d-md-flex col-md-4 col-lg-6 bg-image"></div>
            <div class="col-md-8 col-lg-6">
                <div class="login d-flex align-items-center py-5">
                    <div class="container">
                        <div class="row">
                            <div class="col-md-9 col-lg-8 mx-auto">
                                <h3 class="login-heading mb-4">Bem vindo de volta!</h3>
                                <form>
                                    <div class="form-label-group">
                                        <input type="email" id="inputEmail" class="form-control" placeholder="Email address" required autofocus>
                                        <label for="inputEmail">Email</label>
                                    </div>
                                    <div class="form-label-group">
                                        <input type="password" id="inputPassword" class="form-control" placeholder="Password" required>
                                        <label for="inputPassword">Senha</label>
                                    </div>
                                    <button class="btn btn-lg btn-primary btn-block btn-login text-uppercase font-weight-bold mb-2" type="submit">Acessar</button>
                                    <div class="text-center"><a class="small" href="#" data-toggle="modal" data-target="#esquecisenha">Recuperar senha?</a></div>
                                </form>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!--modal -->
         <div class="modal fade" id="esquecisenha" tabindex="-1" role="dialog" aria-labelledby="exampleModalCenterTitle" aria-hidden="true">
            <div class="modal-dialog modal-dialog-centered" role="document">
                <div class="modal-content">
                    <div class="modal-header">
                        <h5 class="modal-title" id="exampleModalCenterTitle">Recuperação de senha</h5>
                        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                            <span aria-hidden="true">&times;</span>
                        </button>
                    </div>
                    <div class="modal-body">
                        <div class="input-group flex-nowrap">
                            <div class="input-group-prepend">
                                <span class="input-group-text" id="addon-wrapping">@</span>
                            </div>
                            <input type="email" class="form-control" placeholder="Informe seu email" aria-label="Informe seu email" aria-describedby="addon-wrapping">
                        </div>
                    </div>
                    <div class="modal-footer">
                        <button type="button" class="btn btn-primary btn-lg btn-block">Solicitar recuperação</button>
                    </div>
                </div>
            </div>
        </div>
        <!--modal-->
    </div><!-- div nao excluir -->
</template>