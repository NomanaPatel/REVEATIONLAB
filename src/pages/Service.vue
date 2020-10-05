<template>
    <Layout>
        <br/>
        <br/>
        <br/>
        <br/>
        <center>
            <h2 class="title is-2">Boost your <span class="blueclr">digital </span><br/>transformation</h2>
            <div >
            <div class="columns is-inline-flex-desktop pl-5">
                <div class="column " style="margin-top:70px;">
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

                </div>
                <div class="column ">
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
                </div>
                <div class="column" style="margin-top:70px;">
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
                </div>
                </div>
                <div class="columns is-inline-flex-desktop pl-5">
                <div class="column">
                    <Ourservices v-bind:style="{ 'border-color': '#ff6089' }">
                        <template v-slot:header>

                            <g-image class="oursolimg" src="~/assets/Datasci.png" hight="279px"
                                     width="195px"></g-image>

                        </template>
                        <div class="title oursoltitle">Data Science</div>
                        <template v-slot:footer>
                            <div class="oursoltext">
                                We at reveations labs love to deal with alogorithms,maths,statistica with a flare of
                                Programming.
                            </div>
                        </template>
                    </Ourservices>

                </div>
                <div class="column " style="margin-top:-70px;">
                    <Ourservices v-bind:style="{ 'border-color': '#00bbff' }">
                        <template v-slot:header>

                            <g-image class="oursolimg" src="~/assets/Digitalsol.png" hight="279px"
                                     width="195px"></g-image>

                        </template>
                        <div class="title oursoltitle">Blockchain</div>
                        <template v-slot:footer>
                            <div class="oursoltext">
                                Blockchain might sound a new age term.But our highly passionate engineers have been
                                dealing with Blockchain since years and they provide you understand the in-depth of the
                                technology.
                            </div>
                        </template>
                    </Ourservices>

                </div>
                <div class="column ">
                    <Ourservices v-bind:style="{ 'border-color': '#a775ec' }">
                        <template v-slot:header>

                            <g-image class="oursolimg" src="~/assets/Digitalsol.png" hight="279px"
                                     width="195px"></g-image>

                        </template>
                        <div class="title oursoltitle">DevOps</div>
                        <template v-slot:footer>
                            <div class="oursoltext">
                                Reveation Labs deals with new and exciting frameworks such as PLAY providing you with
                                all the latest trendy solutions.
                            </div>
                        </template>
                    </Ourservices>

                </div>
            </div>
            </div>
        </center>

        <br/><br/>
    </Layout>
</template>

<script>
import Ourservices from '~/components/Ourservices.vue';
export default {
  metaInfo: {
    title: 'Service'
  },
  components: {
    Ourservices
  }
}

</script>
<style>

</style>
