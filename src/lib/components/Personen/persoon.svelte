<!-- Personen component -->
<section class="persoon_section">
  <article class="#">
    <h1 class="persoon_naam">Elske Rollema</h1>
  </article>

  <article class="persoon_foto">
    <img
      src="https://i1.wp.com/www.elskerollema.nl/wp-content/uploads/2016/04/elske_rollema.jpeg?w=240&ssl=1"
      alt="Foto van persoon"
    />
  </article>

  <article class="persoon_beschrijving">
    <h2 class="beschrijving_titel">Mijn werk en hobbies ▼</h2>
    <p class="beschrijving">
      Kom in je kracht en krijg inzichten in jezelf. Vind je balans en je eigen
      wijsheid door middel van coaching, counselling, werken met dromen,
      dagdroom therapie, hypnose, etc. Kom langs voor een gratis intake en
      kennismaking.
    </p>
  </article>

  <div class="linkedin-logo">
    <a href="https://nl.linkedin.com/in/elske-rollema-920b052">
      <img
        src="https://upload.wikimedia.org/wikipedia/commons/c/ca/LinkedIn_logo_initials.png?20140125013055"
        class="linkedin-image"
        alt="klikbare linkedin logo"
      /></a
    >
  </div>
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
    display: none;
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
