<script>
    import Header from "./Header.svelte";
    import Footer from "./Footer.svelte";
</script>

<Header />
<main class="container">
    <h2>비보이 브라더스 소개</h2>
    <div class="about">
        <figure class="image">
            <img src="/images/about.jpg" alt="about">
        </figure>
        <div class="content">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam aspernatur odio earum deserunt eaque? Explicabo corrupti, nihil quasi animi eius nam similique, fuga ipsa iusto inventore est veritatis ducimus. Consectetur!</p>
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aspernatur nulla aliquid harum voluptas porro autem asperiores corrupti voluptates, cupiditate maxime esse excepturi totam, reiciendis ipsa sint voluptatibus! Corporis, nihil quasi.</p>
        </div>
    </div>

</main>
<Footer />

<style lang="scss">
    .about {
        display: flex;
        gap: 50px;
        figure, .content { width: 50%; }
        figure img { width: 100%;}
    }
</style>