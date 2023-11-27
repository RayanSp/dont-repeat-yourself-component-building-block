<script>

    import { Title, Image, LinkImage, TitleBeschrijving } from '$lib/index.js'

</script>

<section class="persoon_section">

  <Title />

  <Image />

  <TitleBeschrijving />

  <LinkImage />

</section>

<style>
.persoon_section {
display: flex;
justify-content: center;
flex-direction: column;
text-align: center;
background-color: var(--color-secundary);
padding-top: 1rem;
padding-bottom: 1rem;
}

.persoon_naam {
font-weight: bold;
font-size: 26px;
}

.persoon_foto {
align-self: center;
border: 2px solid var(--color-primary);
width: 15rem;
height: 20rem;
}

.persoon_beschrijving {
align-self: center;
margin-top: 1rem;
width: 15rem;
}

.beschrijving_titel {
font-size: 22px;
text-align: left;
cursor: pointer;
}

.beschrijving {
/* display: block; */
font-size: 16px;
text-align: left;
}

.beschrijving_titel:hover + .beschrijving {
display: block;
}

.linkedin-image {
width: 4rem;
cursor: pointer;
}
</style>
