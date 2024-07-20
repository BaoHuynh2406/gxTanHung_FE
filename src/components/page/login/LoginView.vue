<template>
    <div class="container-fluid login-bg">
        <img src="@/assets/images/hinh_Chua.svg" class="img-fluid position-absolute hinhChua" alt="">
        <img src="@/assets/images/logo_gxTanHung.svg" class="img-fluid position-absolute hinhLogo" alt="">
        <img src="@/assets/images/chu_gxTanHung.svg" class="img-fluid position-absolute hinhChu" alt="">
        <div class="row w-100 m-0">
            <div class="d-flex align-items-center ">
                <div class="col-lg-4 col-md-6 col-sm-8 offset-lg-6 offset-md-6 offset-sm-0">
                    <div class="card">
                        <div class="card-body p-4">
                            <h3 class="card-title text-center mb-4 fw-bold">ĐĂNG NHẬP</h3>
                            <div class="form-group">
                                <label class="fw-bold">Tên đăng nhập: <span class="text-danger">*</span></label>
                                <input name="username" type="text" class="form-control">
                            </div>
                            <div class="form-group">
                                <label class="fw-bold">Mật khẩu: <span class="text-danger">*</span></label>
                                <input name="password" type="password" class="form-control">
                            </div>
                            <div class="form-group d-flex align-items-center justify-content-between">
                                <div class="form-check">
                                    <input type="checkbox" class="form-check-input" id="rememberMe">
                                    <label class="form-check-label" for="rememberMe">Ghi nhớ đăng nhập</label>
                                </div>
                                <a href="#" class="forgot-pass">Quên mật khẩu</a>
                            </div>
                            <div class="text-center">
                                <button class="btn btn-primary">Đăng nhập</button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <!-- content-wrapper ends -->
        </div>
        <!-- row ends -->
    </div>
</template>

<script src="./login.js"></script>

<style scoped>
.login-bg {
    background-image: url('@/assets/images/auth/login_bg_gxTanHung.jpg');
    background-size: cover;
}

.card {
    background-color: rgba(255, 255, 255, 0.2)
}

.hinhChua {
    bottom: 0;
    left: 10%;
    height: auto;
    width: 45%
}

.hinhLogo {
    top: 2%;
    left: 1%;
    height: auto;
    width: 15%
}

.hinhChu {
    top: 2%;
    right: 12%;
    height: auto;
    width: 40%;
}

@media (max-width: 390.98px) {
    .hinhChua {
        display: none;
    }

    .hinhChu {
        top: 6%;
        right: 8%;
        height: auto;
        width: 60%;
    }

    .hinhLogo {
        top: 2%;
        left: 1%;
        height: auto;
        width: 30%
    }
}

@media (max-width: 575.98px) and (min-width: 390.98px) {
    .hinhChua {
        display: none;
    }

    .hinhChu {
        top: 6%;
        right: 8%;
        height: auto;
        width: 60%;
    }

    .hinhLogo {
        top: 2%;
        left: 1%;
        height: auto;
        width: 30%
    }
}

@media (max-width: 767.98px) and (min-width: 575.98px) {
    .login {
        margin-left: 100px;
    }

    .hinhLogo {
        top: 2%;
        left: 1%;
        height: auto;
        width: 30%
    }

    .hinhChu {
        top: 10%;
        right: 8%;
        height: auto;
        width: 50%;
    }

    .hinhChua {
        display: none;
    }
}

@media (max-width: 991.98px) and (min-width: 767.98px) {
    .hinhChua {
        bottom: 0;
        left: 5%;
        height: auto;
        width: 50%;
    }

    .hinhLogo {
        top: 2%;
        left: 1%;
        height: auto;
        width: 25%
    }

    .hinhChu {
        top: 10%;
        right: 12%;
        height: auto;
        width: 50%;
    }
}

@media (max-width: 1199.98px) and (min-width: 991.98px) {
    .hinhLogo {
        top: 2%;
        left: 1%;
        height: auto;
        width: 20%
    }

    .hinhChua {
        bottom: 0;
        left: 10%;
        height: auto;
        width: 60%
    }

    .hinhChu {
        top: 10%;
        right: 6%;
        height: auto;
        width: 40%;
    }
}

@media (max-width: 1399.98px) and (min-width: 1199.98px) {
    .hinhLogo {
        top: 2%;
        left: 1%;
        height: auto;
        width: 20%
    }

    .hinhChua {
        bottom: 0;
        left: 10%;
        height: auto;
        width: 60%
    }

    .hinhChu {
        top: 5%;
        right: 6%;
        height: auto;
        width: 40%;
    }
}
</style>