<template>
    <div class="container-fluid">
       <div class="row contact">
            <div class="col-md-3"></div>
            <div class="col-md-2 icon text-center">
                <img class="contact-image" src="../../assets/img/location.png" alt="apoe4 location">
                <h5 class="contact-heading mt-5">ADDRESS</h5>
                <p class="address">3 Birrel Ave, Yaba 100001, Lagos</p>
            </div>
            <div class="col-md-2 icon text-center">
                <img class="contact-image" src="../../assets/img/phonecall.png" alt="call apoe4">
                <h5 class="contact-heading mt-5">CALL US</h5>
                <div class="link">
                <a href="tel:+2348012334590" class="contact-link">+2348012334590</a>
                <br/>
                <a href="tel:+2348012345678" class="contact-link">+2348012345678</a>
                </div>
                
            </div>
            <div class="col-md-2 icon text-center">
                <img class="contact-image mb-3" src="../../assets/img/mail.png" alt="mail apoe4">
                <h5 class="contact-heading mt-5">SAY HELLO</h5>
                <div class="link">
                <a href="mailto:apoe4@hng.com" class="contact-link">apoe4@hng.com</a>
                <br/>
                <a href="mailto:hello@apoe4.com" class="contact-link">hello@apoe4.com</a>
                </div>
                
            </div>
            <div class="col-md-3"></div>
       </div>
            <!-- ALL COMPONENT MARKUP GOES HERE-->
            

            
        
    </div>
</template>

<style scoped>
        .container{
            margin-top: 80px;
            display: flex;
            flex-flow: row wrap;
            justify-content: center;
            align-items: baseline;
        }
        .contact{
            padding-top: 50px;
            padding-bottom: 50px;

        }
        .contact .address{
            font-size:13px;
            color:black;
            margin-top:-10px;


        }
        .contact .contact-heading{
            font-weight: bold;
            margin-bottom: 20px;
            font-size: 16px;

        }

        .contact .icon {
            padding-top: 50px;
            padding-bottom: 50px;
        }

        .contact .contact-link{
            text-transform: lowercase;
            font-size: 14px;
        }

        .contact a {
            font-weight: 200;
        }

        .contact .link{
            margin-top:-10px;

        }
        
       
</style>

<script>
export default {
    data() {
        return {
            
        }
    },
}
</script>
