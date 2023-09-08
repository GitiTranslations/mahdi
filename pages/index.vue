<template>
    <NuxtLayout>
        <div class=" text-slate-300">
            <section id="about" class="main w-full h-[100vh] relative bg-fixed mt-10" style="background-image: url(pic1.webp)">
                <!-- <img src="pic1.webp" alt="pic1" class="absolute opacity-50" /> -->
                <div class="absolute top-[40%] p-10 bg-gradient-to-r from-purple-500 to-pink-500">
                    <h1 class="text-4xl font-bold">Welcome to Giti Translations</h1>
                    <h2 class="text-2xl font-thin italic text-slate-50">Your Trusted Translation Partner</h2>
                    <p class="text-xl my-5 ">
                        About Giti Translations – “Expert Translation Services”


Welcome to Giti Translations, your trusted partner for expert translation services that transcend language boundaries. Our dedicated team of linguists and translators is committed to delivering precise and culturally resonant translations, ensuring your global reach and success.
Founded on the principles of integrity, quality, and client satisfaction, [Your Agency Name] has emerged as a leader in the translation industry. With extensive experience spanning various industries and sectors, our expertise enables businesses to expand internationally, individuals to connect seamlessly, and organizations to communicate with impact.
At Giti Translations, we specialize in translating legal documents, technical manuals, marketing collateral, and website localization. Our mission is to facilitate effective cross-cultural communication, breaking down language barriers to help you thrive in a global marketplace.
Discover the [Your Agency Name] advantage, where words open doors to new opportunities and possibilities. Explore our services and experience the difference that expertise and a global perspective can make.
Welcome to Giti Translations—where words connect worlds.

                    </p>
                </div>
            </section>

            <section id="services">
                <h2 class="section-title">Our Services</h2>
                <div class="services">
                    <div class="card">
                        <div class="service-title">
                            Document Translation
                        </div>
                        <div class="service-description">
                            We provide accurate translations of legal documents, marketing materials, academic papers, and
                            more. Rest assured, your content will maintain its original intent and tone.
                        </div>
                    </div>
                    <div class="card">
                        <div class="service-title">
                            Expert Translation Services
                        </div>
                        <div class="service-description">
                            Our skilled interpreters excel in live events, meetings, and conferences, facilitating effective
                            cross-cultural communication.
                        </div>
                    </div>
                    <div class="card">
                        <div class="service-title">
                            Certified Translations
                        </div>
                        <div class="service-description">
                            Need certified translations for official documents? We provide accurate, legally recognized
                            translations for immigration, legal, and academic purposes.
                        </div>
                    </div>

                </div>
            </section>

            <section id="pricing">
                <h1 class="section-title">Pricing</h1>
                <div>
                    <div class="card">
                        <div class="pricing-description">
                            At MahT, we believe in transparency. Our pricing is competitive and tailored to your specific
                            project requirements. We offer flexible pricing models, including per-word rates, hourly rates
                            for interpretation, and custom quotes for large-scale projects. Contact us today for a
                            personalized quote and discover the value of our professional translation services.
                        </div>
                    </div>
                </div>
            </section>

            <section id="contact">
                <h1 class="section-title">Contact Us</h1>
                <div class="text-center text-xl">
                    <h2 class="text-xl my-1">Get in Touch with MahT</h2>
                    <p class="my-2">
                        Ready to start a conversation about your translation needs? Our dedicated team is here to assist
                        you. Contact us today for a free consultation, quote, or any inquiries you may have.
                    </p>

                    <ul>
                        <li>
                        Email: giti.translations@gmail.com
                        </li>
                        <li>
                        Phone: [Insert Phone Number]
                        </li>
                        <li>
                            Address: [Insert Address]
                        </li>
                        <li>
                            Social Media: [Insert Social Media Links]
                        </li>
                    </ul>
                    <div>
                        Let us help you break language barriers and connect with the world. Giti Translations - Your
                        Global Communication Partner.
                    </div>
                </div>
            </section>
        </div>
    </NuxtLayout>
</template>

<style scoped>
section {
    @apply my-10 py-3 w-full sm:w-8/12 mx-auto;
}

.section-title {
    @apply my-10 text-4xl font-bold text-center uppercase;
}

.services {
    list-style: none;
    @apply flex justify-center gap-10;
}

.services .card {
    @apply w-3/12 px-7 py-5 text-center text-[1.08rem] text-slate-200 rounded-md bg-gradient-to-r from-sky-500 to-indigo-500 hover:from-sky-600 hover:to-indigo-600 cursor-pointer;
}

.service-title {
    @apply text-xl font-bold text-center my-5;
}


.pricing-description {
    @apply text-xl text-center;
}</style>
