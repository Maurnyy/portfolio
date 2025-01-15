<script>
  let visible = false;
  let visibleForum = false;
  let visibleNotify = false;

  function toggleVissible() {
    visible = !visible;
    if (visibleForum || visibleNotify) {
      if (visibleForum) {
        visibleForum = !visibleForum;
      } else {
        visibleNotify = !visibleNotify;
      }
    }
  }
  function toggleVissibleForum() {
    visibleForum = !visibleForum;
    if (visible || visibleNotify) {
      if (visible) {
        visible = !visible;
      } else {
        visibleNotify = !visibleNotify;
      }
    }
  }
  function toggleVissibleNotify() {
    visibleNotify = !visibleNotify;
    if (visible || visibleForum) {
      if (visible) {
        visible = !visible;
      } else {
        visibleForum = !visibleForum;
      }
    }
  }
</script>

<div class="ml-20">
  <div class="flex flex-col gap-y-36 max-w-5x1 mx-auto px-4 my-24 print:my-0">
    <section class="flex flex-col gap-y-16">
      <div class="flex flex-col gap-4">
        <h1 class="text-3xl md:text-6xl trackin-wide">
          <span class="font-bold">Ticorporate</span>
        </h1>
        <div class="md:text-xl tracking-wide">Project Elli</div>
        <p>
          <span class="font-bold mr-6 underline">
            <a href="/">Etusivu</a>
          </span>
          <span class="font-bold underline">
            <a href="/ticorporate">Ticorporate</a>
          </span>
        </p>
      </div>
      <div
        class="leading-loose [&amp;_a]:font-bold [&amp;_a]:underline font-mono"
      >
        <h2
          class="font-bold text-purple-500 text-3xl bg-clip-text fill-transparent bg-gradient-to-tl from-blue-500 to-red-500 mr-2 mb-4"
          style="-webkit-text-fill-color: transparent"
        >
          Projektin yleiskuva
        </h2>
        <p>
          <strong>Projekti Elli</strong> on toimeksianto Elisalta, jossa rakennetaan
          alusta Elisan ja Jamkin väliselle yhteistyölle. Alustan tarkoituksena on
          parantaa kommunikaatiota ja läpinäkyvyyttä mahdollisten organisaatioiden
          yhteistöiden välillä. Projekti kesti noin 4 kuukautta ja siihen oli käytettävissä
          450 tuntia per ryhmän jäsen.
        </p>
        <br />
        <p>
          Olin osa kuuden hengen ryhmää, ja roolini oli toimia <strong
            >Fullstack-kehittäjänä</strong
          >, <strong>Product Ownerina</strong> ja vastata
          <strong>liiketalous suunnitelmasta</strong>.
        </p>
        <br />
        <p><strong>Sovelluksen tavoitteet:</strong></p>
        <p>
          <strong>Sovelluksessa osapuolten tulee nähdä vuosinäkymä</strong>,
          jossa on ilmoituksia mahdollisista projektiyhteistöistä. Osapuolten
          tulee pystyä lisäämään uusia projektiyhteistöitä ja muokkaamaan omia
          postauksiaan. Lisäksi sovelluksen käyttäjien tulee pystyä kirjautumaan
          sovellukseen ja siitä ulos. Sovelluksen tulee täyttää WCAG 2.2
          saavutettavuusvaatimukset. Sovelluksen tulee pyöriä
          AWS-pilviympäristössä, olla korkeasti käytettävä ja testattu.
          Sovelluksessa tulee olla peruskäyttäjän lisäksi pääkäyttäjän rooli,
          joka pystyy hallinnoimaan muita käyttäjiä.
        </p>
      </div>
      <div
        class="leading-loose [&amp;_a]:font-bold [&amp;_a]:underline font-mono"
      >
        <h2
          class="font-bold text-purple-500 text-3xl bg-clip-text fill-transparent bg-gradient-to-tl from-blue-500 to-red-500 mr-2 mb-4"
          style="-webkit-text-fill-color: transparent"
        >
          Projektin aloitus ja lähtökohdat
        </h2>

        <div>
          <h2 class="font-bold text-1xl bg-clip-text mr-2 mt-8">
            Ennen projektia:
          </h2>
          <p>
            <strong>Kurssin alussa saimme tehtäväksi suunnitella</strong> mahdollinen
            sovellusidea pareittain. Minun alkuperäinen idea oli suunnitella ERP-sovellus
            rakennusalalle. Vaikka minulla oli intoa lähteä suunnittelemaan ERP-sovellusta
            ja selkeä visio siihen, niin koin, että oppimisen kannalta olisi järkeveämpi
            hakea asiakasprojektiin.
          </p>
        </div>
        <div>
          <h2 class="font-bold text-1xl bg-clip-text mr-2 mt-8">
            Lähtökohdat:
          </h2>
          <p>
            <strong>En osannut odottaa projektilta mitään</strong> ja aiempi
            kokemus projekti työskentelyltä oli koulun ryhmäraportit ja viikon
            mittainen IT-projekti Software Engineer opintojaksolla. Minulla ei
            ollut myöskään kokemusta <strong>Scrumista</strong>, vaikka tiesin
            kyseisen metodin ja sitä oltiin opiskeltu Software Engineer
            opintojaksolla.
          </p>
          <br />
          <p>
            <strong>Alunperin minun piti toimia projektissa</strong> pelkästään
            <strong>Fullstack-kehittäjänä</strong>
            ja liiketalous osaajana. Olimme keskustelleet ryhmän kanssa Product Ownerin
            roolin valitsemisesta ja tarkoituksena oli valita se vasta ensimmäisen
            yhteisen palaverin jälkeen, mutta Aleksi oli kuullut väärin ja esitteli
            minut <strong>Product Ownerina</strong> Elisalle. Vaikka sain roolin
            vahingossa, niin koin selviäväni siitä maaliin. Kurssin alussa en asettanut
            itselleni liiketalouden osalta mitään tavoitteita, mutta halusin kehittyä
            paremmaksi koodariksi.
          </p>
          <br />
          <p>
            <strong>Ryhmällämme</strong> ei ollut aluksi minkäänlaista visiota
            projektin toteutuksesta, mutta koimme, että haluamme toteuttaa
            sovelluksen <strong>Angularilla</strong>, sillä meillä oli vahvin
            osaaminen siihen. Halusimme kuitenkin kokeilla jotain uutta, joten
            valitsimme Standalonen. Aiemmat projektit olimme toteuttaneet
            no-standalonena.
          </p>
          <br />
          <p><strong>Projekti Ellin aloitus:</strong></p>
          <p>
            <strong>Projekti lähti liikkeelle siitä</strong>, että lähdimme
            tutkimaan oppilaitoksen ja Elisan tarpeita. Käytimme n. 2 viikkoa
            aikaa haastatteluihin, suunnitteluun ja ux karvalankamallin
            rakentamiseen. Tässä vaiheessa olin oman mukavuusalueen ulkopuolella
            ja tuntui, että olen hieman hukassa projektin kanssa. Kuitenkin mitä
            pidemmälle saimme suunniteltua projektia, niin sitä vahvemmaksi tuli
            visio siitä miten se voitaisiin toteuttaa.
          </p>
          <br />
          <p>
            <strong>Koin projektin alussa</strong>, että haluan lähteä vahvasti
            rakentamaan tietokantaa ja ottaa vastuulle lomakkeen rakentamisen
            frontin ja backendin puolella. Backendin osalta lähdimme
            liikenteeseen sillä, että AD rakenti Node Expressin pohjan ja minä
            lähdin suunnittelemaan miten Mongo tietokanta toteutettaisiin
            lomakkeen osalta.
          </p>
        </div>
      </div>

      <div
        class="leading-loose [&amp;_a]:font-bold [&amp;_a]:underline font-mono"
      >
        <h2
          class="font-bold text-purple-500 text-3xl bg-clip-text fill-transparent bg-gradient-to-tl from-blue-500 to-red-500 mr-2 mb-4"
          style="-webkit-text-fill-color: transparent"
        >
          Projektin aikainen toteutus
        </h2>
        <div>
          <button
            class="btn btn-outline bg-gradient-to-tl from-blue-500 to-red-500 text-white"
            on:click={toggleVissible}>Template esimerkki</button
          >
          {#if visible}
            <button
              class="btn btn-outline bg-gradient-to-tl from-blue-500 to-red-500 text-white"
              on:click={toggleVissibleForum}>Forum post esimerkki</button
            >
            <button
              class="btn btn-outline bg-gradient-to-tl from-blue-500 to-red-500 text-white"
              on:click={toggleVissibleNotify}>Notifikaatio esimerkki</button
            >
            <img
              class="mt-4"
              src="/assets/project_TS.png"
              alt="Project template Typescript"
            />

            <p>Kuva 1. Lähetettävän datan alustaminen ja lähettäminen</p>
            <br />
            <img
              src="/assets/project_checkbox.png"
              alt="Project template checkbox"
            />
            <p>
              Kuva 2. Checkbox tarkistus, että onko klikattu ja klikattujen
              arvon muuttaminen trueksi.
            </p>
            <br />

            <img src="/assets/project.png" alt="Project template" />

            <p>Kuva 3. Templaatin ulkonäkö verkkosivuilla</p>
          {/if}

          <button
            class="btn btn-outline bg-gradient-to-tl from-blue-500 to-red-500 text-white"
            on:click={toggleVissibleForum}>Forum post esimerkki</button
          >
          {#if visibleForum}
            <button
              class="btn btn-outline bg-gradient-to-tl from-blue-500 to-red-500 text-white"
              on:click={toggleVissibleNotify}>Notifikaatio esimerkki</button
            >
            <img
              class="mt-4"
              src="/assets/backend_addForumPost.png"
              alt="Add new forum post"
            />
            <p>Kuva 1. Forum postauksen lisäys backend</p>
            <br />
            <img
              src="/assets/frontend_ForumPost.png"
              alt="Add forum post frontend"
            />
            <p>Kuva 2. Forum postauksen lisäys frontin puolella</p>
            <br />

            <img
              src="/assets/backend_ForumPostDelete.png"
              alt="Delete new forum post"
            />
            <p>Kuva 3. Forum postauksen poisto</p>
            <br />
            <img src="/assets/forum_interface.png" alt="Forum interface" />
            <p>Kuva 4. Forum postauksen interface</p>
          {/if}
          <button
            class="btn btn-outline bg-gradient-to-tl from-blue-500 to-red-500 text-white"
            on:click={toggleVissibleNotify}>Notifikaatio esimerkki</button
          >
          {#if visibleNotify}
            <img
              class="mt-4"
              src="/assets/notifikaation_lahetys.png"
              alt="sending notification"
            />
            <p>
              Kuva 1. Haetaan kaikkien kommentoijien ja postauksen tekijän id ja
              lähetetään tietokantaan.
            </p>
            <br />
            <img
              src="/assets/Notification_markAsRead.png"
              alt="sending notification"
            />
            <p>
              Kuva 2. Notifikaation merkkaus luetuksi, navikointi ja ajan
              formatointi.
            </p>
            <br />

            <img src="/assets/notification_new.png" alt="New notification" />
            <p>Kuva 3. Uusi notifikaatio</p>
            <br />
            <img src="/assets/notification_read.png" alt="Notification read" />
            <p>Kuva 4. Luettu notifikaatio</p>
          {/if}
        </div>
      </div>

      <div
        class="leading-loose [&amp;_a]:font-bold [&amp;_a]:underline font-mono"
      >
        <h2
          class="font-bold text-purple-500 text-3xl bg-clip-text fill-transparent bg-gradient-to-tl from-blue-500 to-red-500 mr-2 mb-4"
          style="-webkit-text-fill-color: transparent"
        >
          Projektin jälkeen
        </h2>
        <h1 class="font-bold text-2xl">Opitut asiat</h1>
        <p>
          <strong>Ticorporaten aikana suurimmat kehitykset</strong> tulivat ongelmanratkaisussa,
          Githubin käytössä ja projektityöskentelyssä. Opin myös, että ei kannata
          jäädä tutkimaan yhtä ongelmaa liian pitkäksi aikaa, vaan hypätä seuraavaan
          asiaan ja palata myöhemmin kyseiseen ongelmaan tuoreilla avoilla.
        </p>
        <br />
        <h1 class="font-bold text-2xl">Itsereflektio</h1>
        <p>
          <strong>Ticorporate-työpanokseni tuntimääräisesti</strong> oli noin
          450 työtuntia mukaanlukien portfolion rakentaminen. Projektin alussa
          jouduin heti epämukavuusalueella, kun odotin pääseväni koodaaman heti
          alkuun, mutta jouduinkin suunnittelemaan sovelluksen sisältöä.
          Kuitenkin jälkeenpäin ajateltuna sovelluksen suunnittelu loi minulle
          pohjan ja selkeän vision sovelluksen rakentamiseen. Koin myös
          hyödyllisenä sen, että aloitimme päivän 15-minuutin palaverilla, jossa
          kävimme ryhmänkesken läpi mitä kukin tekee päivän aikana.
          <strong>Elisa</strong> tuki myös valtavasti projektia, sillä he osallistuivat
          muutamaa päivää lukuunottamatta jokaiseen Scrum-tapaamiseen ja suunnitteluun.
        </p>
        <br />
        <p>
          <strong>Opin valtavasti Product Owner työssä</strong>, vaikka olin
          alussa lähinnä kuuntelijan roolissa. Elisa onneksi tuki tässä
          työtehtävässä valtavasti ja opetti kuinka backlog kannattaa rakentaa.
        </p>
        <br />
        <p>
          <strong>Ohjelmoinissa pystyin hyödyntämään</strong> esimerkiksi Frontend-sovelluskehityksen
          ja Backend 1 -kurssilla opittuja asioita esimerkiksi lomakkeiden käytössä.
          Vaikka ohjelmoinnissa ei tullutkaan suoraan mitään täysin uutta, ongelmanratkaisutaidot
          kehittyivät huomattavasti. Alussa valitsimme Flowbite UI kirjaston, sillä
          sen avulla pystyisimme rakentamaan Datepickerin ja kalenterin helposti.
          Kuitenkin tässä vaiheessa minulla ei ollut riittävää osaamista näkemään,
          että ongelma saattaa olla jossain muualla kuin omassa koodissa. Lähtökohtaisesti
          ajattelin, että oma koodi oli viallinen, kun valitsin kalenterista päivän
          18.1.2025, mutta se tallentui tietokantaan lähetyshetken päivämääränä.
          Kamppailin ongelman kanssa muutaman viikon ja myös eräällä ryhmäläisellä
          oli samanlaisia haasteita. Päätimme lopulta yhdessä vaihtaa kirjastoksi
          Angular Materials. Angular Materials vaihdon jälkeen datepicker toimi ja
          ei tarvinnut tehdä muutoksia omaan koodiin. Olin siis tehnyt "turhaa" työtä,
          mutta tämän turhan työn ansiosta opin lukemaan paremmin koodia.
        </p>
        <br />
        <p>
          <strong>Uutena asiana tuli notifikaation rakentaminen.</strong> Yritin
          etsiä netistä tietoa, että miten voisin rakentaa sen ja yritin myös kysyä
          ChatGPT:ltä, mutta en löytänyt mitään tietoa siitä. Tämän jälkeen rupesin
          pohtimaan miten käyttäjä saa ilmoituksen ja mitä tapahtuu, kun se saa ilmoituksen.
          Tästä opin ajattelemaan asioita tietokanta näkökulmasta, sekä sen, että
          isot kokonaisuudet on hyvä pilkkoa pieniin osiin ja ratkaista vasta sen
          jälkeen.
        </p>
        <br />
        <p>
          <strong>Olen hyvin tyytyväinen omaan panokseeni Ticorporatessa</strong
          > ja mielestäni hoidin oman osuuteni esimerkillisesti. Olen tyytyväinen
          opittuihin asioihin vaikka koodin tasolla ei aina ollut kauneinta. Ticorporate
          vahvisti ajatuksiani siitä, mitä haluan tehdä työkseni, ja ymmärsin, että
          tarvitsen lisää kokemusta kasvaakseni paremmaksi ohjelmoijaksi. Koen, että
          minulla on vahvuus tietokannoissa.
        </p>
      </div>
      <div
        class="flex flex-row gap-2 justify-center md:justify-start [&amp;_a]:p-2"
      >
        <a
          href="https://github.com/Maurnyy/"
          target="_blank"
          rel="noreferrer nofollow"
          aria-label="Github profile for Mauri Nyyssönen"
        >
          <svg viewBox="0 0 128 128" height="1.5rem" width="1.5rem">
            <g fill="#181616">
              <path
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M64 5.103c-33.347 0-60.388 27.035-60.388 60.388 0 26.682 17.303 49.317 41.297 57.303 3.017.56 4.125-1.31 4.125-2.905 0-1.44-.056-6.197-.082-11.243-16.8 3.653-20.345-7.125-20.345-7.125-2.747-6.98-6.705-8.836-6.705-8.836-5.48-3.748.413-3.67.413-3.67 6.063.425 9.257 6.223 9.257 6.223 5.386 9.23 14.127 6.562 17.573 5.02.542-3.903 2.107-6.568 3.834-8.076-13.413-1.525-27.514-6.704-27.514-29.843 0-6.593 2.36-11.98 6.223-16.21-.628-1.52-2.695-7.662.584-15.98 0 0 5.07-1.623 16.61 6.19C53.7 35 58.867 34.327 64 34.304c5.13.023 10.3.694 15.127 2.033 11.526-7.813 16.59-6.19 16.59-6.19 3.287 8.317 1.22 14.46.593 15.98 3.872 4.23 6.215 9.617 6.215 16.21 0 23.194-14.127 28.3-27.574 29.796 2.167 1.874 4.097 5.55 4.097 11.183 0 8.08-.07 14.583-.07 16.572 0 1.607 1.088 3.49 4.148 2.897 23.98-7.994 41.263-30.622 41.263-57.294C124.388 32.14 97.35 5.104 64 5.104z"
              ></path>
              <path
                d="M26.484 91.806c-.133.3-.605.39-1.035.185-.44-.196-.685-.605-.543-.906.13-.31.603-.395 1.04-.188.44.197.69.61.537.91zm2.446 2.729c-.287.267-.85.143-1.232-.28-.396-.42-.47-.983-.177-1.254.298-.266.844-.14 1.24.28.394.426.472.984.17 1.255zM31.312 98.012c-.37.258-.976.017-1.35-.52-.37-.538-.37-1.183.01-1.44.373-.258.97-.025 1.35.507.368.545.368 1.19-.01 1.452zm3.261 3.361c-.33.365-1.036.267-1.552-.23-.527-.487-.674-1.18-.343-1.544.336-.366 1.045-.264 1.564.23.527.486.686 1.18.333 1.543zm4.5 1.951c-.147.473-.825.688-1.51.486-.683-.207-1.13-.76-.99-1.238.14-.477.823-.7 1.512-.485.683.206 1.13.756.988 1.237zm4.943.361c.017.498-.563.91-1.28.92-.723.017-1.308-.387-1.315-.877 0-.503.568-.91 1.29-.924.717-.013 1.306.387 1.306.88zm4.598-.782c.086.485-.413.984-1.126 1.117-.7.13-1.35-.172-1.44-.653-.086-.498.422-.997 1.122-1.126.714-.123 1.354.17 1.444.663zm0 0"
              ></path>
            </g>
          </svg>
        </a>
        <a
          href="https://www.linkedin.com/in/maurinyyssonen/"
          target="_blank"
          rel="noreferrer nofollow"
          aria-label="LinkedIn profile for Mauri Nyyssönen"
        >
          <svg viewBox="0 0 128 128" height="1.5rem" width="1.5rem">
            <path
              d="M116 3H12a8.91 8.91 0 00-9 8.8v104.42a8.91 8.91 0 009 8.78h104a8.93 8.93 0 009-8.81V11.77A8.93 8.93 0 00116 3zM39.17 107H21.06V48.73h18.11zm-9-66.21a10.5 10.5 0 1110.49-10.5 10.5 10.5 0 01-10.54 10.48zM107 107H88.89V78.65c0-6.75-.12-15.44-9.41-15.44s-10.87 7.36-10.87 15V107H50.53V48.73h17.36v8h.24c2.42-4.58 8.32-9.41 17.13-9.41C103.6 47.28 107 59.35 107 75z"
            ></path>
          </svg>
        </a>
        <a href="mailto:mauri.nyyssonen@live.fi">mauri.nyyssonen@live.fi</a>
      </div>
    </section>
  </div>
</div>
