<template>
    <section class="p-5" id="questions">
        <div class="container">
            <h2 class="text-center mb-4">FAQ</h2>
            <div class="accordion accordion-flush" id="questions">
            <!-- Item 1 -->
            <div class="accordion-item">
                <h2 class="accordion-header">
                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#question-one">
                    Where are you located?
                </button>
                </h2>
                <div id="question-one" class="accordion-collapse collapse" data-bs-parent="#questions">
                <div class="accordion-body">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ullam sed doloribus quia. Delectus tempore ratione ex dolorem fugit. Deleniti, natus? Tempore explicabo sed, blanditiis, quaerat assumenda molestiae dolore maxime dolorem porro iusto excepturi cum, quidem doloremque! Aperiam sapiente omnis illum repellendus provident alias accusamus deleniti eius corporis, doloremque asperiores. Eligendi.</div>
                </div>
            </div>
            <!-- Item 2 -->
            <div class="accordion-item">
                <h2 class="accordion-header">
                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#question-two">
                    How much does it cost to attend?
                </button>
                </h2>
                <div id="question-two" class="accordion-collapse collapse" data-bs-parent="#questions">
                <div class="accordion-body">Placeholder content for this accordion, which is intended to demonstrate the <code>.accordion-flush</code> class. This is the second item's accordion body. Let's imagine this being filled with some actual content.</div>
                </div>
            </div>
            <!-- Item 3 -->
            <div class="accordion-item">
                <h2 class="accordion-header">
                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#question-three">
                    What do I need to know?
                </button>
                </h2>
                <div id="question-three" class="accordion-collapse collapse" data-bs-parent="#questions">
                <div class="accordion-body">Placeholder content for this accordion, which is intended to demonstrate the <code>.accordion-flush</code> class. This is the third item's accordion body. Nothing more exciting happening here in terms of content, but just filling up the space to make it look, at least at first glance, a bit more representative of how this would look in a real-world application.</div>
                </div>
            </div>
            <!-- Item 4 -->
            <div class="accordion-item">
                <h2 class="accordion-header">
                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#question-four">
                    How do I sign up?
                </button>
                </h2>
                <div id="question-four" class="accordion-collapse collapse" data-bs-parent="#questions">
                <div class="accordion-body">Placeholder content for this accordion, which is intended to demonstrate the <code>.accordion-flush</code> class. This is the third item's accordion body. Nothing more exciting happening here in terms of content, but just filling up the space to make it look, at least at first glance, a bit more representative of how this would look in a real-world application.</div>
                </div>
            </div>
            <!-- Item 5 -->
            <div class="accordion-item">
                <h2 class="accordion-header">
                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#question-five">
                    Do you help me find a job?
                </button>
                </h2>
                <div id="question-five" class="accordion-collapse collapse" data-bs-parent="#questions">
                <div class="accordion-body">Placeholder content for this accordion, which is intended to demonstrate the <code>.accordion-flush</code> class. This is the third item's accordion body. Nothing more exciting happening here in terms of content, but just filling up the space to make it look, at least at first glance, a bit more representative of how this would look in a real-world application.</div>
                </div>
            </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'FAQView',
    props: {}
}
</script>

<style></style>