<template>
    <div class="intro-slider">
        <div class="intro-section overlay bg-cover" :style="{ backgroundImage: `url('/images/hero-image/hero-3.jpg')` }">
            <div class="container">
                <div class="row row-cols-lg-1 row-cols-1">
                    <div class="col align-self-center">
                        <div class="intro-content m-auto text-center">
                            <vue-typed-js class="justify-content-center"
                                :strings="['Business', 'Inspiration', 'Technology']" 
                                :loop="true" 
                                :typeSpeed="150"
                                :backSpeed="80"
                                :showCursor="false">
                                <h2 class="title">Techminate<span class="typing"></span></h2>
                            </vue-typed-js>
                            <div class="desc">
                                <p>We are an agency located in Bangladesh. We think strategy, craft design, develop digital and create motion. To forward your brand and business.</p>
                            </div>
                             
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>