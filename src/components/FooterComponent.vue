<template>
    <footer class="py-5 px-4">
        <h1 data-aos="fade-up">The Digital One-Stop-Shop For <br> Institutional Real Estate</h1>
        <hr>
        <div class="row mb-5">
            <div class="col-md-4 mt-4" data-aos="fade-up">
                <h3>Get In Touch</h3>
                <p class="footer-paragraph mt-3 w-75">Contact us today to see the power of the StegX Ecosystem in
                    action!</p>
                <div class="input-container mt-4">
                    <input class="input-footer" maxlength="256" name="email" placeholder="Your e-mail" type="email"
                        required>
                    <span class="input-icon">
                        <svg xmlns="http://www.w3.org/2000/svg" width="22" height="22" fill="currentColor"
                            class="bi bi-arrow-right-circle-fill" viewBox="0 0 16 16">
                            <path
                                d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0M4.5 7.5a.5.5 0 0 0 0 1h5.793l-2.147 2.146a.5.5 0 0 0 .708.708l3-3a.5.5 0 0 0 0-.708l-3-3a.5.5 0 1 0-.708.708L10.293 7.5z" />
                        </svg>
                    </span>
                </div>

            </div>
            <div class="col-md-4 my-4 bordered" data-aos="fade-up">
                <h3>Get In Touch</h3>
                <p class="footer-paragraph mt-3 w-75">StegX GmbH, <br> Platz der Einheit 2 <br> c/o Techquartier
                    <br>60327 Frankfurt
                </p>
            </div>
            <div class="col-md-4 mt-4 ps-4" data-aos="fade-up">
                <h3>Connect with us</h3>
                <div class="footer-icon mt-4"><svg xmlns="http://www.w3.org/2000/svg" width="40" height="40"
                        fill="currentColor" class="bi bi-linkedin" viewBox="0 0 16 16">
                        <path
                            d="M0 1.146C0 .513.526 0 1.175 0h13.65C15.474 0 16 .513 16 1.146v13.708c0 .633-.526 1.146-1.175 1.146H1.175C.526 16 0 15.487 0 14.854zm4.943 12.248V6.169H2.542v7.225zm-1.2-8.212c.837 0 1.358-.554 1.358-1.248-.015-.709-.52-1.248-1.342-1.248S2.4 3.226 2.4 3.934c0 .694.521 1.248 1.327 1.248zm4.908 8.212V9.359c0-.216.016-.432.08-.586.173-.431.568-.878 1.232-.878.869 0 1.216.662 1.216 1.634v3.865h2.401V9.25c0-2.22-1.184-3.252-2.764-3.252-1.274 0-1.845.7-2.165 1.193v.025h-.016l.016-.025V6.169h-2.4c.03.678 0 7.225 0 7.225z" />
                    </svg></div>
            </div>
        </div>
        <hr>
        <div class="d-flex justify-content-between copy-write" data-aos="fade-up">
            <p class="footer-paragraph">© StegX GmbH. All Rights Reserved 2024</p>
            <div>
                <ul class="d-flex">
                    <li>
                        <a class="ms-5" href="">StegXplained</a>
                    </li>
                    <li>
                        <a class="ms-5" href="">About StegX</a>
                    </li>
                    <li>
                        <a class="ms-5" href="">Imprint</a>
                    </li>
                </ul>
            </div>
        </div>

    </footer>
</template>

<style scoped>
footer {
    background-image: linear-gradient(135deg, #781fff 15%, #3f0efa);
    font-family: "Montserrat";
}

footer h1 {
    font-weight: 600;
    font-size: 3rem;
    margin: 8% 0;
}

footer h3 {
    font-weight: bold;
}

.footer-paragraph {
    color: rgba(255, 255, 255, .7);
}


.input-container {
    position: relative;
    display: inline-block;
}

.input-footer {
    width: 100%;
    padding-right: 30px;
    color: #fff;
    background-color: transparent;
    border: 0;
    border-bottom: 1px solid rgba(255, 255, 255, .7);
}

.input-icon {
    position: absolute;
    top: 50%;
    right: 10px;
    transform: translateY(-50%);
    color: white;
}

.bordered {
    border-left: 1px solid #9164d4;
    border-right: 1px solid #9164d4;
    padding: 0 20px;
}

.footer-icon {
    color: #fff;
    background-color: #4c02bb71;
    padding: 15px 20px;
    border-radius: 10px;
    display: inline-block;
}

li {
    list-style: none;
}

li a {
    text-decoration: none;
    color: #fff;
    font-size: 1.1rem;
    letter-spacing: 2px;
    font-weight: 600;
}

.copy-write {
    margin: 5% 0;
}
</style>