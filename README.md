# TCC_Leaning_Page

Código para criar botões de rede sociais
HTML>
 <a href="#" title="Linkedin" rel="nofollow" target="_blank">
        <div class="btn-social">
            <i class="fa fa-linkedin fa-2x" aria-hidden="true"></i>
        </div>
    </a>
    <a href="#" title="Instagram" rel="nofollow" target="_blank">
        <div class="btn-social">
            <i class="fa fa-instagram fa-2x" aria-hidden="true"></i>
        </div>
</div>

CSS>
.social-buttons-custom {
        position: fixed;
        top: 50%;
        right: 20px;
        transform: translate(0, -50%);
        display: flex;
        flex-direction: column;
        z-index: 999999;
    }

    .social-buttons-custom a {
        text-decoration: none;
    }

    .btn-social {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 50px;
        width: 50px;
        background-color: #2e5381;
        border-radius: 100%;
        border: 1px solid transparent;
        padding: 10px;
        margin-bottom: 15px;
    }

    .btn-social .fa {
        color: #fff;
        transition: .3s all ease-in;
    }

    .btn-social:hover {
        transform: scale(1.1);
        transition: .3s all ease-in;
        border: 1px solid #fff;
    }
