<template>
    <div class="main-content iq-contact">
        <!-- Contact Us -->
        
        <section class="iq-our-touch pt-5">
            <div class="container">
                <div class="iq-get-in ">
                    <div class="row">
                        <div class="col-lg-6 col-md-12 col-sm-12 iq-mtb-15">
                            <h4 class="heading-left title text-black">Get in Touch</h4>
                            <form id="contact" method="post">
                                <div class="contact-form">
                                    <div class="section-field iq-mt-10">
                                        <input class="require" id="contact_name" type="text" placeholder="Name*" name="name"><br>
                                    </div>
                                    <div class="section-field iq-mt-10">
                                        <input class="require" id="contact_email" type="email" placeholder="Email*" name="email"><br>
                                    </div>
                                    <div class="section-field iq-mt-10">
                                        <input class="require" id="contact_phone" type="text" placeholder="Phone*" name="phone"><br>
                                    </div>
                                    <div class="section-field textarea iq-mt-10">
                                        <textarea id="contact_message" class="input-message require" placeholder="Comment*" rows="5" name="message"></textarea><br>
                                    </div>
                                    <div class="section-field">
                                    <div class="g-recaptcha" data-sitekey="6Lc5XV4UAAAAAJzUmGomye9Peru8lXyzT22FH0lX"><br></div>
                                </div>
                                    <a  href=""  class="button pull-right iq-mt-20">Send Message</a>
                                    <p role="alert"></p>
                                </div>
                            </form>
                        </div> 
                        <div class="col-lg-6 col-md-12 col-sm-12 iq-mtb-15">
                            <div class="contact-info  pt-0 ">
                                <h4 class="heading-left title text-black">Contact Us</h4>
                                <div class="iq-contact-box media mb-3">
                                    <div class="iq-icon left">
                                        <i aria-hidden="true" class="ion-ios-location-outline"></i>
                                    </div>
                                    <div class="contact-box right media-body">
                                        <h5 class="iq-tw-6">Address Of Saudia Arabia Office</h5>
                                        <p>Second Floor Olaya Mall, King Fahad Rd Riyadh, Saudi Arabia</p>
                                        <h5 class="iq-tw-6">Address of Pakistan Office</h5>
                                        <p>Third Floor Gold Point Mall, Murre Road Rawalpindi, Pakistan</p>

    

                                    </div>
                                </div>
                                <div class=".iq-contact-box right media mb-3 ">
                                    <div class="iq-icon left">
                                        <i aria-hidden="true" class="ion-ios-telephone-outline"></i>
                                    </div>
                                    <div class="contact-box right media-body">
                                        <h5 class="iq-tw-6">Phone</h5>
                                        <span class="lead iq-tw-5">+966 505 465 830</span>
                                        <span class="lead iq-tw-5">+92 336 923 7827</span>
                                        <p class="">Mon-Fri 9:00am - 5:00pm</p>
                                    </div>
                                </div>
                                <div class=".iq-contact-box right media mb-3 ">
                                    <div class="iq-icon left">
                                        <i aria-hidden="true" class="ion-ios-email-outline"></i>
                                    </div>
                                    <div class="contact-box right media-body">
                                        <h5 class="iq-tw-6">Mail</h5>
                                        <span class="lead iq-tw-5">sales@asaheeb.co</span>
                                        <span class="lead iq-tw-5">nbashir@intercraftsol.com</span>
                                        <p class="">24 X 7 online support</p>
                                    </div>
                                </div>
                               
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!-- Contact Us End -->
       
    </div>
</template>
<script>
    export default {
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>

 