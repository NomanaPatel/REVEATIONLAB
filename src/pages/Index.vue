<template>
    <Layout>
        <div class="home">
            <br/>
            <br/>
            <br/>
            <br/><br/><br/><br/>

            <center>
                <div style="420px">
                    <ClientOnly>
                        <carousel :perPageCustom=[[370,1],[1199,1]] :navigationClickTargetSize=0 :autoplay="true"
                                  :loop="true" :navigationEnabled="true" :paginationEnabled="false"
                                  paginationColor='#2444EB' paginationActiveColor="#2444EB">
                            <slide><h2 class="title is-2">A perfect gateway for<br/> all<br/><span
                                    class="blueclr">digital </span>solutions</h2> <h6 class="title is-6 belowdigital">
                                Lorem
                                ipsmorttitor blandit accumsan. Ut vel dictum sem,<br/>
                                pretium dui. malesuada enim in dolor euismod.</h6></slide>
                            <slide><h2 class="title is-2">A perfect gateway for<br/> all<br/><span
                                    class="blueclr">digital </span>solutions slide2</h2> <h6
                                    class="title is-6 belowdigital">Lorem ipsmorttitor blandit accumsan. Ut vel dictum
                                sem,<br/>
                                pretium dui. malesuada enim in dolor euismod.</h6></slide>
                            <slide><h2 class="title is-2">A perfect gateway for<br/> all<br/><span
                                    class="blueclr">digital </span>solutions slide3</h2> <h6
                                    class="title is-6 belowdigital">Lorem ipsmorttitor blandit accumsan. Ut vel dictum
                                sem,<br/>
                                pretium dui. malesuada enim in dolor euismod.</h6></slide>
                            <slide><h2 class="title is-2">A perfect gateway for<br/> all<br/><span
                                    class="blueclr">digital </span>solutions slide4</h2> <h6
                                    class="title is-6 belowdigital">Lorem ipsmorttitor blandit accumsan. Ut vel dictum
                                sem,<br/>
                                pretium dui. malesuada enim in dolor euismod.</h6></slide>
                        </carousel>
                    </ClientOnly>
                </div>
            </center>

            <br/><br/>

            <center>
                <div class="columns">
                    <div class="column">
                        <div class="is-hidden-mobile" style="margin-top:240px;">
                            <g-image src="~/assets/Group.png" :responsive="true" width="71px" height="55px"></g-image>
                        </div>
                    </div>
                    <div class="column">
                        <g-image src="~/assets/banner.png" :responsive="true" hight="378px" width="360px"></g-image>
                    </div>
                    <div class="column">
                        <div class="is-hidden-mobile">
                            <g-image src="~/assets/Group.png" :responsive="true" width="71px" height="55px"></g-image>
                        </div>
                    </div>
                </div>
            </center>
            <br/><br/>

            <center>
            <div class="scrollmenu ourservicecarousel">
                <nav class="level back">
                    <h6 class="lavel-item has-text-centered title is-6  mt-5 py-3 belowdigital">TOP CLIENTS</h6>
                    <p class="level-item has-text-centered">
                        <g-image src="~/assets/Top-c1.png" hight="100px" width="100px"></g-image>
                    </p>
                    <p class="level-item has-text-centered">
                        <g-image src="~/assets/Top-c2.png" hight="100px" width="100px"></g-image>
                    </p>
                    <p class="level-item has-text-centered">
                        <g-image src="~/assets/Top-c3.png" hight="100px" width="100px"></g-image>
                    </p>

                    <p class="level-item has-text-centered">
                        <g-image src="~/assets/Top-c4.png" hight="100px" width="100px"></g-image>
                    </p>
                    <p class="level-item has-text-centered">
                        <g-image src="~/assets/Top-c5.png" hight="100px" width="100px"></g-image>
                    </p>
                    <p class="level-item has-text-centered">
                        <g-image src="~/assets/Top-c1.png" hight="100px" width="100px"></g-image>
                    </p>

                    <p class="level-item has-text-centered">
                        <g-image src="~/assets/Top-c2.png" hight="100px" width="100px"></g-image>
                    </p>
                    <p class="level-item has-text-centered">
                        <g-image src="~/assets/Top-c3.png" hight="100px" width="100px"></g-image>
                    </p>
                    <p class="level-item has-text-centered">
                        <g-image src="~/assets/Top-c4.png" hight="100px" width="100px"></g-image>
                    </p>
                    <p class="level-item has-text-centered">
                        <g-image src="~/assets/Top-c5.png" hight="100px" width="100px"></g-image>
                    </p>
                </nav>
            </div>
            </center>
            <br/>
           
                <center>
                <div class="ourservicecarousel" style="text-align:justify"><h2 class="title is-3 ">Our Core <span class="blueclr"> Services</span>
                </h2></div>
                </center>
                <center>
                <div class="ourservicecarousel" style="text-align:right"><span class="fa fa-chevron-left pt-5 "></span><span
                        class="fa fa-chevron-right pt-5 pl-3"></span></div>
                </center>
              
            <center>
                <div>

                    <div class="ourservicecarousel">
                        <ClientOnly>
                            <carousel :perPageCustom=[[370,1],[1199,3]] :navigationClickTargetSize=0 :autoplay="true"
                                      :loop="false" :navigationEnabled="true" paginationColor='#2444EB'
                                      paginationActiveColor="#2444EB">
                                <slide>
                                    <Ourservices v-bind:style="{ 'border-color': '#ff6089' }">
                                        <template v-slot:header>

                                            <g-image class="oursolimg" src="~/assets/Digitalsol.png" hight="279px"
                                                     width="195px"></g-image>

                                        </template>
                                        <div class="title oursoltitle">Digital Solutions Art</div>
                                        <template v-slot:footer>
                                            <div class="oursoltext">
                                                We at Reveation Labs provide you with the best of Digital Solutions. Be
                                                it
                                                any technology out team makes sure you get the best service
                                            </div>
                                        </template>
                                    </Ourservices>
                                </slide>
                                <slide>
                                    <Ourservices v-bind:style="{ 'border-color': '#00bbff' }">
                                        <template v-slot:header>
                                            <g-image class="oursolimg" src="~/assets/Mobilitysol.png" hight="279px"
                                                     width="195px"></g-image>
                                        </template>
                                        <div class="title oursoltitle">Mobility Solutions</div>
                                        <template v-slot:footer>
                                            <div class="oursoltext">
                                                We love developing Mobile Applications and our team of expertise has a
                                                special affinity to program next generation of Mobile Applications
                                                beacause
                                                we believe this is where the future is!
                                            </div>
                                        </template>
                                    </Ourservices>
                                </slide>
                                <slide>
                                    <Ourservices v-bind:style="{ 'border-color': '#a775ec' }">
                                        <template v-slot:header>
                                            <g-image class="mb-6 oursolimg" src="~/assets/Cloudsol.png" hight="170px"
                                                     width="195px"></g-image>
                                        </template>
                                        <div class="title oursoltitle">Cloud Based Solutions</div>
                                        <template v-slot:footer>
                                            <div class="oursoltext">
                                                As the world move towards cloud based solutions. Reveation Labs has a
                                                dedicated team which makes the perfect use of cloud based solutions
                                            </div>
                                        </template>
                                    </Ourservices>
                                </slide>
                                <slide>
                                    <Ourservices v-bind:style="{ 'border-color': '#ff6089' }">
                                        <template v-slot:header>

                                            <g-image class="oursolimg" src="~/assets/Digitalsol.png" hight="279px"
                                                     width="195px"></g-image>

                                        </template>
                                        <div class="title oursoltitle">Digital Solutions Art</div>
                                        <template v-slot:footer>
                                            <div class="oursoltext">
                                                We at Reveation Labs provide you with the best of Digital Solutions. Be
                                                it
                                                any technology out team makes sure you get the best service
                                            </div>
                                        </template>
                                    </Ourservices>
                                </slide>
                                <slide>
                                    <Ourservices v-bind:style="{ 'border-color': '#00bbff' }">
                                        <template v-slot:header>
                                            <g-image class="oursolimg" src="~/assets/Mobilitysol.png" hight="279px"
                                                     width="195px"></g-image>
                                        </template>
                                        <div class="title oursoltitle">Mobility Solutions</div>
                                        <template v-slot:footer>
                                            <div class="oursoltext">
                                                We love developing Mobile Applications and our team of expertise has a
                                                special affinity to program next generation of Mobile Applications
                                                beacause
                                                we believe this is where the future is!
                                            </div>
                                        </template>
                                    </Ourservices>
                                </slide>
                                <slide>
                                    <Ourservices v-bind:style="{ 'border-color': '#a775ec' }">
                                        <template v-slot:header>
                                            <g-image class="mb-6 oursolimg" src="~/assets/Cloudsol.png" hight="170px"
                                                     width="195px"></g-image>
                                        </template>
                                        <div class="title oursoltitle">Cloud Based Solutions</div>
                                        <template v-slot:footer>
                                            <div class="oursoltext">
                                                As the world move towards cloud based solutions. Reveation Labs has a
                                                dedicated team which makes the perfect use of cloud based solutions
                                            </div>
                                        </template>
                                    </Ourservices>
                                </slide>
                            </carousel>
                        </ClientOnly>
                    </div>
                </div>
            </center>

           
          <center>
               
                <div  class="ourworkbackground1" ><h2 class="title is-3 py-4">Our <span class="blueclr"> Work</span></h2>
                </div>
            </center>
          
            <center>
                
                <div class="ourworkbackground">

                    <div class="    is-mobile is-multiline is-centered scrollmenu1  is-inline-flex-desktop">
                        <div class="column ourworktop">
                            <Ourwork>
                                <template v-slot:header>
                                    <div class="columns">
                                        <div class="column ">
                                            <div class="ourworktitle1 has-text-weight-semibold ">&bull; Cloud
                                                Structure
                                            </div>
                                        </div>
                                    </div>
                                    <div class="ourworktitle">Lorem ipsum dolor sit amet.</div>
                                </template>
                                <div class="ourworkimg">
                                    <g-image class="" src="~/assets/Proj1.png" hight="308px" width="168px"></g-image>
                                </div>
                                <template v-slot:footer>
                                    <div class="ourworktext">
                                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut pretium pretium
                                        tempor. Ut.
                                    </div>
                                </template>
                            </Ourwork>
                        </div>
                        <div class="column ourworktop">
                            <Ourwork>
                                <template v-slot:header>
                                    <div class="columns">
                                        <div class="column ">
                                            <div class="ourworktitle2 has-text-weight-semibold">&bull; Web Development
                                            </div>
                                        </div>
                                    </div>
                                    <div class="ourworktitle">Lorem ipsum dolor sit amet.</div>
                                </template>
                                <div class="ourworkimg">
                                    <g-image class="" src="~/assets/Proj2.png" hight="308px" width="168px"></g-image>
                                </div>
                                <template v-slot:footer>
                                    <div class="ourworktext">
                                        Fusce vehicula dolor arcu, sit amet blandit dolor mollis nec. Donec viverra
                                        eleifend la.
                                    </div>
                                </template>
                            </Ourwork>
                        </div>
                        <div class="column ourworktop">
                            <Ourwork>
                                <template v-slot:header>
                                    <div class="columns">
                                        <div class="column ">
                                            <div class="ourworktitle3 has-text-weight-semibold">&bull; Block Chain</div>
                                        </div>
                                    </div>
                                    <div class="ourworktitle">Lorem ipsum dolor sit amet.</div>
                                </template>
                                <div class="ourworkimg">
                                    <g-image class="" src="~/assets/Proj3.png" hight="308px" width="168px"></g-image>
                                </div>
                                <template v-slot:footer>
                                    <div class="ourworktext">
                                        Nam dapibus nisl vitae elit fringilla rutrum. Aenean sollicitudin, erat a
                                        elementum.
                                    </div>
                                </template>
                            </Ourwork>
                        </div>
</div>
                          <div class="    is-mobile is-multiline is-centered scrollmenu1  is-inline-flex-desktop">
                        <div class="column">
                            <Ourwork>
                                <template v-slot:header>
                                    <div class="columns">
                                        <div class="column ">
                                            <div class="ourworktitle4 has-text-weight-semibold">&bull; Web/mobile
                                                App
                                            </div>
                                        </div>
                                    </div>
                                    <div class="ourworktitle">Lorem ipsum dolor sit amet.</div>
                                </template>
                                <div class="ourworkimg">
                                    <g-image class="" src="~/assets/Proj4.png" hight="308px"
                                             width="168px"></g-image>
                                </div>
                                <template v-slot:footer>
                                    <div class="ourworktext">
                                        In hac habitasse platea dictumst. Vivamus adipiscing fermentum quam volutpat
                                        aliquam..
                                    </div>
                                </template>
                            </Ourwork>
                        </div>
                        <div class="column">
                            <Ourwork>
                                <template v-slot:header>
                                    <div class="columns">
                                        <div class="column ">
                                            <div class="ourworktitle5 has-text-weight-semibold">&bull; Data
                                                Science
                                            </div>
                                        </div>
                                    </div>
                                    <div class="ourworktitle">Lorem ipsum dolor sit amet.</div>
                                </template>
                                <div class="ourworkimg">
                                    <g-image class="" src="~/assets/Proj5.png" hight="308px"
                                             width="168px"></g-image>
                                </div>
                                <template v-slot:footer>
                                    <div class="ourworktext">
                                        Curabitur lobortis id lorem id bibendum. Ut id consectetur magna. Quisque
                                        volutpat aug.
                                    </div>
                                </template>
                            </Ourwork>
                        </div>
                        <div class="column">
                            <Ourwork>
                                <template v-slot:header>
                                    <div class="columns">
                                        <div class="column ">
                                            <div class="ourworktitle6 has-text-weight-semibold">&bull; DevOps</div>
                                        </div>
                                    </div>
                                    <div class="ourworktitle">Lorem ipsum dolor sit amet.</div>
                                </template>
                                <div class="ourworkimg">
                                    <g-image class="" src="~/assets/Proj6.png" hight="308px"
                                             width="168px"></g-image>
                                </div>
                                <template v-slot:footer>
                                    <div class="ourworktext">
                                        Vestibulum rutrum quam vitae fringilla tincidunt. Suspendisse nec tortor
                                        urna. Ut laore.
                                    </div>
                                </template>
                            </Ourwork>
                        </div>
                    </div>
                    </div>
               
                
            </center>
            <br/><br/>
            <div class="columns py-6">
                <div class="column">
                    <center>
                   
                    </center>
                    <center>
                        <g-link class="button viewall_btn is-button-text-color">
                            <strong>VIEW ALL</strong>
                        </g-link>
                    </center>
                </div>
            </div>

           <center>
                <div class="testibackground1">
                    <div class="title is-3">Donec facilisis tortor ut augue lacinia, at viverra est semp.
                    </div>
                </div>
           </center>
            <center>
                <div class="testibackground" style="padding-top: 18px;">  

                    <div class="scrollmenu1 is-inline-flex-desktop pad">
                        <div class="column ">
                            <CTS>
                                <template v-slot:header>
                                    <div>
                                        <g-image class="ctsimg" src="~/assets/Commitment.svg" hight="84px"
                                                 width="84px"></g-image>
                                    </div>
                                </template>
                                <div class="ctstitle">
                                    Commitment
                                </div>
                                <template v-slot:footer>
                                    <div class="ctstext">
                                        Reveation labs has the next level of commitment which provides you with a smooth
                                        sailing
                                    </div>
                                </template>
                            </CTS>
                        </div>
                        <div class="column ">
                            <CTS>
                                <template v-slot:header>
                                    <div>
                                        <g-image class="ctsimg" src="~/assets/TechDriven.svg" hight="84px"
                                                 width="84px"></g-image>
                                    </div>
                                </template>
                                <div class="ctstitle">
                                    Tech Driven
                                </div>
                                <template v-slot:footer>
                                    <div class="ctstext">
                                        Reveations Labs has the tendency to turn your Business Idea into a Digital
                                        Solution
                                    </div>
                                </template>
                            </CTS>
                        </div>
                        <div class="column">
                            <CTS>
                                <template v-slot:header>
                                    <div>
                                        <g-image class="ctsimg" src="~/assets/Satisfication.svg" hight="84px"
                                                 width="84px"></g-image>
                                    </div>
                                </template>
                                <div class="ctstitle">
                                    Satisfication
                                </div>
                                <template v-slot:footer>
                                    <div class="ctstext">
                                        Our core values lies in providing satisfication to our estemmed clients
                                    </div>
                                </template>
                            </CTS>
                        </div>
                    </div>
                </div>

            </center>

            <center>
                <div class="outertestimonial">
                    <div class="columns">
                        <div class="column ">
                            <div class="mt-6 is-hidden-mobile same">
                                <div class="ovaltesti overtesti">
                                    <g-image src="~/assets/Oval-testimonial.png" width="380px" height="400px"></g-image>
                                </div>
                                <div class="client1">
                                    <g-image src="~/assets/client-1.png" height="91px" width="91px"></g-image>
                                </div>
                                <div class="client2">
                                    <g-image src="~/assets/client-2.png" height="71px" width="71px"></g-image>
                                </div>
                                <div class="strips">
                                    <g-image src="~/assets/stripes.png" height="79px" width="68.8px"></g-image>
                                </div>
                                <div class="clienttext">
                                    <b>What's Our Client Say About Us.</b>
                                </div>
                                <div class="client3">
                                    <g-image src="~/assets/client-3.png" height="67px" width="67px"></g-image>
                                </div>
                                <div class="client4">
                                    <g-image src="~/assets/client-4.png" height="47px" width="47px"></g-image>
                                </div>
                            </div>


                            <div class="column ">

                                <div>
                                    <g-image class="comma1 ucomma" src="~/assets/Comma1.svg"></g-image>
                                </div>

                                <div class="card cardlayout card-width">
                                    <div class="oneofclient" style="padding:20px;">
                                        Fusce vehicula dolor arcu, sit amet blandit dolor mollis nec. Donec viverra
                                        eleifend la. Fusce vehicula dolor arcu, sit amet blandit dolor mollis nec. Donec
                                        viverra eleifend la ipsome sit.
                                    </div>
                                    <div class="oneofclientimg">
                                        <g-image src="~/assets/Nancy.png"></g-image>
                                    </div>
                                    <div>
                                        <span class="oneofclientname has-text-weight-semibold">Nancy Jenkins </span><br/>
                                        <p class="oneofclientname1">Development Manager, Honda</p>
                                    </div>
                                    <div class="larrow">
                                        <g-image src="~/assets/arrow-left.svg"></g-image>
                                    </div>
                                    <div class="rarrow">
                                        <g-image src="~/assets/arrow-right.svg"></g-image>
                                    </div>
                                </div>

                                <div>
                                    <g-image class="comma2 dcomma" src="~/assets/Comma2.svg"></g-image>
                                </div>
                            </div>
                        </div>

                    </div>
                </div>
            </center>
            
            <center>
            <div class="contactusdesignouter" style="text-align:justify">
                <div class="title-is-new title is-3">Have a project in mind?</div>
                <div class="title is-6 ">We are located close to Heart of Digital & Technological capital in East
                    Coast.
                </div>
            </div>
            </center>
          
            <center>
                <div class="contactusdesignouter">
                    <div class="columns">
                        <div class="column  pt-6 mt-6">
                            <div class="contactusdesign ml-4">
                                <form action="https://formspree.io/f/xgepovoq" method="POST">
                                    <ClientOnly>
                                        <FloatingLabel :config="{label: '',color:{lineColor: '#2444eb'}}">
                                            <input class="py-3 myinput1" placeholder="What's Your Name?"
                                                   name="sender_name">
                                        </FloatingLabel>
                                    </ClientOnly>
                                    <div class="columns">
                                        <div class="column">
                                            <ClientOnly>
                                                <FloatingLabel :config="{label: '',color:{lineColor: '#2444eb'}}">
                                                    <input class="py-3 myinput2"
                                                           placeholder="Drop Email here to know more"
                                                           name="sender_email" type="email" >
                                                </FloatingLabel>
                                            </ClientOnly>
                                        </div>
                                        <div class="column">
                                            <ClientOnly>
                                                <FloatingLabel :config="{label: '',color:{lineColor: '#2444eb'}}">
                                                    <input class="py-3 myinput2"
                                                           placeholder="Do we have your phone number ?"
                                                           name="sender_phoneno" type="tel" pattern="^[6-9]\d{9}$">
                                                </FloatingLabel>
                                            </ClientOnly>
                                        </div>
                                    </div>
                                    <ClientOnly>
                                        <FloatingLabel :config="{label: '',color:{lineColor: '#2444eb'}}">
                                            <input class="pb-3 myinput1"
                                                   placeholder="Please enter your physical address"
                                                   name="sender_address">
                                        </FloatingLabel>
                                    </ClientOnly>
                                    <ClientOnly>
                                        <FloatingLabel :config="{label: '',color:{lineColor: '#2444eb'}}">
                                            <input class="py-3 myinput1"
                                                   placeholder="Write here about your queries"
                                                   name="sender_query">
                                        </FloatingLabel>
                                    </ClientOnly>
                                    <button type="submit" class="button my-5 ml-3 submitbtn " style="color:#2444eb;"><strong>SUBMIT</strong>
                                    </button>
                                </form>
                            </div>

                        </div>

                        <br/><br/><br/>
                        <div class="column">
                            <g-image class="mr-6 is-hidden-mobile" src="~/assets/Bottom-banner.png" hight="437px"
                                     width="570px"></g-image>
                        </div>
                    </div>
                </div>
            </center>
        </div>
    </Layout>
</template>

<script>
import Ourservices from '~/components/Ourservices.vue';
import Ourwork from '~/components/Ourwork.vue';
import Casestudies from '~/components/Casestudies.vue';
import CTS from '~/components/CTS.vue';
import FloatingLabel from 'vue-simple-floating-labels'

export default {
  components: {
    Ourservices,
    Ourwork,
    Casestudies,
    CTS,
     Carousel: () =>
        import ('vue-carousel/src/index')
        .then(m => m.Carousel)
        .catch(),
      Slide: () =>
        import ('vue-carousel/src/index')
        .then(m => m.Slide)
        .catch(),
    FloatingLabel
  },

}




</script>

<page-query>
    query {
    allOurworkcollection {
    edges {
    node {
    id
    title
    descriptions
    }
    }
    }
    }
</page-query>
<style>
body{
overflow-x:hidden;
}
 
@media screen and (max-width: 1100px) {
    
.oneofclientimg{
width:53.6px;
height:53.6px;
margin-left:24px;
float:left;
}
.oneofclientname{
margin-left:13px;
float:left;
font-size: 21.5px;
color: #1C1C1C;
letter-spacing: 0;
}
.oneofclientname1{
margin-top:0px;
margin-right:140px;
font-size: 14.32px;
color: #B4B4B4;
letter-spacing: 0;
}
    .larrow{
margin-top:15px;
float:left;
margin-left:20px;
}
.rarrow{
 margin-top:15px;
 float:left;
 margin-left:5px;
}
    .ourworkbackground1
    {
        width: 100%;
        text-align:justify;
    }
    .testibackground1
    {
         width: 100%;
        text-align:justify;
    }
    .ucomma
    {
        margin-right: 290px;
        width:50px;
    }
    .dcomma
    {
        width:50px;
        margin-left: 900px;
    }
    
    .cardlayout{
       height:290px;
         width: 35%;
        margin-left:600px;
       
        z-index:1;
        border: 1px solid #979797;
        border-radius: 8.4px;
        }
    .overtesti
    {
        width:230px;
    }
    .outertestimonial
{
    width:100%;
}
    div.scrollmenu1 {
        width:100%;
 display: flex;
  flex-wrap: nowrap;
  overflow-x: auto;
  
}
    .testibackground{
    padding-top:30px;
    height:375px;
    width:100%;
    background-color:rgba(87,123,249,0.1);
    }
    
    .ourservicecarousel {
    width: 100%;
    }

    }



@media screen and (max-width: 1000px) {
    
    .ucomma
    {
        margin-right: 0px;
        margin-top: 0px;
    }
    .dcomma {
    margin-top: 0px;
    margin-left: 0px;
}
    .card-width{
        width: 0%;
        margin-left:0px;
    }
  .myinput1 {
    width:335px;
  }
  .myinput2{
    width:335px;
  }
  .same{
  display:none;
  }
  .ovaltesti {
  display:none;
  }
  .client1{
  display:none;
  }
  .client2{
  display:none;
  }
  .client3{
  display:none;
  }
  .client4{
  display:none;
  }
  .stripes{
  display:none;
  }
  .clienttext{
  display:none;
  }
  .haveproj{
  margin-top:350px;
  margin-left:20px;
  }
  .comma1{
  width:56px;
  height:44px;
float:left;
position:relative;
 top:15px;
 left:15px;
 z-index:2;
}
.comma2{
width:56px;
height:44px;
float:left;
position: relative;
 bottom:15px;
 left:270px;
 z-index:2;
}
.cardlayout{
height:270px;
width:380px;
float:left;
z-index:1;
border: 1px solid #979797;
border-radius: 8.4px;
}
.oneofclientimg{
width:53.6px;
height:53.6px;
margin-left:24px;
float:left;
}
.oneofclientname{
margin-left:13px;
float:left;
font-size: 21.5px;
color: #1C1C1C;
letter-spacing: 0;
}
.oneofclientname1{
margin-top:0px;
margin-right:140px;
font-size: 14.32px;
color: #B4B4B4;
letter-spacing: 0;
}
.larrow{
margin-top:15px;
float:left;
margin-left:20px;
}
.rarrow{
 margin-top:15px;
 float:left;
 margin-left:5px;
}
.ourservicecarousel{
width:100%;
}
div.scrollmenu1 {
 display: flex;
  flex-wrap: nowrap;
  overflow-x: auto;
  
}
div.scrollmenu1 div{
  flex: 0 0 auto;
}
.ourworkbackground1{
padding-top:30px;
width:1200px;
text-align:justify;
overflow:hidden;
}
.ourworkbackground{
padding-top:30px;
height:990px;
width:100%;
background-color:rgba(87,123,249,0.1);
overflow:auto;
}
.testibackground1{
padding-top:30px;
text-align: justify;
width:100%;
}
.contactusdesignouter{
width:100%;
}
.title-is-new
{
    width:100%;
    height:20px;
    text-align: left;
    margin-top: 390px;
    margin-bottom: 10px;
} 
.outertestimonial
{
    width:100%;
}
.testibackground{
padding-top:30px;
height:375px;
width:100%;
background-color:rgba(87,123,249,0.1);
}
}

@media screen and (min-width: 1100px) {


  .myinput1 {
    width:700px;
  }
  .myinput2{
    width:335px;
  }
  .haveproj{
  margin-top:50px;
  margin-left:20px;
  }
  .comma1{
  width:70px;
  height:55px;
float:left;
position:relative;
 top:20px;
 right:80px;
 z-index:2;
}
.comma2{
width:70px;
  height:55px;
float:left;
position:relative;
 bottom:20px;
 left:790px;
 z-index:2;
}
.cardlayout{
height:330px;
width:490px;
float:left;
z-index:1;
border: 1px solid #979797;
border-radius: 8.4px;
}
.oneofclient{
text-align:left;
font-size: 17.9px;
color: #1C1C1C;
}
.oneofclientimg{
width:67px;
height:67px;
margin-left:30px;
float:left;

}
.oneofclientname{
margin-left:13px;
float:left;
font-size: 26.88px;
color: #1C1C1C;
letter-spacing: 0;
}
.oneofclientname1{
margin-top:0px;
margin-right:120px;
font-size: 17.9px;
color: #B4B4B4;
letter-spacing: 0;
line-height: 26.88px;
}
.larrow{
margin-top:70px;
float:left;
margin-left:-70px;
}
.rarrow{
 margin-top:70px;
 float:left;
 margin-left:-40px;
}
.ourservicecarousel{
width:1200px;
}

.ourworkbackground{
padding-top:30px;
height:990px;
width:1200px;
background-color:rgba(87,123,249,0.1);
overflow:hidden;
}
.ourworkbackground1{
padding-top:30px;
width:1200px;
text-align:justify;
overflow:hidden;
}
.testibackground{
padding-top:30px;
height:375px;
width:1200px;
background-color:rgba(87,123,249,0.1);
}
.testibackground1{
padding-top:30px;
text-align: justify;
width:1200px;
}
.contactusdesign{
width:700px;
}
.contactusdesignouter{
width:1200px;
}
.outertestimonial{
width:1300px;
}
div.scrollmenu1 {
  display: flex;
  flex-wrap: nowrap;
  
  
}
pad
{
    padding: 20px;
}
div.scrollmenu1 div{
  flex: 0 0 auto;
}
}

div.scrollmenu {
  overflow: auto;
  white-space: nowrap;
  
}

div.scrollmenu nav h6{
  display: inline-block;
  text-align: center;
  padding: 14px;
}
div.scrollmenu nav p{
  display: inline-block;
  color: white;
  text-align: center;
  padding: 14px;
  text-decoration: none;
}


.viewall_btn{
width:181.4px;
height:40.3px;
color:#2444eb;
border: 1px solid #2444EB;
border-radius: 4.2px;
border-radius: 4.2px;
}
.submitbtn {
  border-color: #2444eb;
  background-color: transparent;
  border-radius: 6px;
  float:left;
}
.home{
height:100%;
width:100%;
}
.blueclr{
color:#2444EB;

  box-shadow: 0px 8px 6px 5px gray;

}
.back{
background-color: #F7FAFF;
}
.belowdigital{
font-family:Rubik-Regular;
color:#B4B4B4;
}
.oursolimg{
margin-top:85px;
margin-left:46px;
margin-right:45px;
margin-bottom:57px;
}
.oursoltitle{
width:290px;
margin-top:0px;
margin-left:46px;
margin-right:46px;
margin-bottom:0px;
font-size: 26.88px;
color: #1C1C1C;
letter-spacing: 0;
text-align: center;
}
.oursoltext{
font-size: 17.9px;
color: #1C1C1C;
letter-spacing: 0;
text-align: center;
line-height: 26.88px;
margin-top:8px;
margin-left:23px;
margin-right:23px;
margin-bottom:34px;
}
.drag{
margin-bottom:0px;
margin-left:750px;
}
.ourworktitle{
width:307px;
height:64px;
font-size:26.88px;
letter-spacing: 0;
margin-left:30px;
margin-right:33px;
margin-top:20.7px;
margin-bottom:0px;
text-align: left;
}
.ourworkimg{
width:308px;
height:168px;
margin-left:30px;
margin-right:32px;
margin-top:16px;
margin-bottom:0px;
}
.ourworktext{
width:300px;
height:81px;
margin-left:30px;
margin-right:40px;
margin-top:20px;
margin-bottom:30px;
text-align: left;
}
.ourworktitle1{
width:152.1px;
height:35.3px;
margin-left:30px;
margin-right:187.9px;
margin-top:30px;
border:1px solid transparent;
color:#0099FF;
background-color:rgba(85,204,243,0.1);
border-radius:30.41px;
font-size: 14.6px;
letter-spacing: 0;
}
.ourworktitle2{
width:152.1px;
height:35.3px;
margin-left:30px;
margin-right:187.9px;
margin-top:30px;
border:1px solid transparent;
color:#FAB612;
background-color:rgba(255,212,78,0.1);
border-radius:30.41px;
font-size: 14.6px;
letter-spacing: 0;
}
.ourworktitle3{
width:152.1px;
height:35.3px;
margin-left:30px;
margin-right:187.9px;
margin-top:30px;
border:1px solid transparent;
color:#577BF9;
background-color:rgba(87,123,249,0.1);
border-radius:30.41px;
font-size: 14.6px;
letter-spacing: 0;
}
.ourworktitle4{
width:152.1px;
height:35.3px;
margin-left:30px;
margin-right:187.9px;
margin-top:30px;
border:1px solid transparent;
color:#1C1C1C;
background-color:rgba(238,238,238,1);
border-radius:30.41px;
font-size: 14.6px;
letter-spacing: 0;
}
.ourworktitle5{
width:152.1px;
height:35.3px;
margin-left:30px;
margin-right:187.9px;
margin-top:30px;
border:1px solid transparent;
color:#FE2E65;
background-color:rgba(254,46,101,0.1);
border-radius:30.41px;
font-size: 14.6px;
letter-spacing: 0;
}
.ourworktitle6{
width:152.1px;
height:35.3px;
margin-left:30px;
margin-right:187.9px;
margin-top:30px;
border:1px solid transparent;
color:#7C463D;
background-color:rgba(167,107,91,0.1);
border-radius:30.41px;
font-size: 14.6px;
letter-spacing: 0;
}
.ctsimg{
margin-left:143px;
margin-right:143px;
margin-top:34px;
}
.ctstitle{
width:170px;
height:32px;
margin-left:100px;
margin-right:100px;
margin-top:29px;
font-size: 26.88px;
color: #1C1C1C;
letter-spacing: 0;
}
.ctstext{
width:299.9px;
height:80.6px;
margin-left:35px;
margin-right:35.1px;
margin-top:14px;
margin-bottom:41.4px;
}

	div.ovaltesti {
  float:left;
  position:relative;
  z-index:1;
}
div.client1 {
  float:left;
  position:relative;
  top:150px;
  right:150px;
  bottom:0px;
  z-index:2;
}
div.client2{
  float:left;
  position:relative;
  top:0px;
  right:60px;
}
div.strips{
  float:left;
  position:relative;
  top:70px;
  left:40px;
}
div.clienttext{
width:148px;
height:78px;
font-size:21.34px;
 float:left;
 position:relative;
 top:150px;
 right:240px;
}
div.client3{
float:left;
 position:relative;
 top:280px;
 right:190px;
}
div.client4{
float:left;
 position:relative;
 top:340px;
 right:440px;
}

.vfl-label {
display:none;
}

.vfl-label-on-input {
  top: -1em;

}
.vfl-label + input {
  font-size: 100%;
  color:#2444EB;
  border: 0;
  border-bottom: 2px solid #aaa;
  transition: border 0.2s;
}
.vfl-label-on-focus + input {
  border-bottom: 2px solid #2444EB;
}






</style>

