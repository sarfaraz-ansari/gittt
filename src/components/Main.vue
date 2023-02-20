<template>
  <div class="odd">
    <h1>About Me</h1>
    <p>
      Hey, I’m Sarfaraj Ansari. I’m a student and a web developer living in
      Lucknow. I am a fan of technology and beautiful UI. I’m also interested in
      web development, programming and learning new technology. I am currently
      working on vuejs 3 framework to enhance my skills to make awesome frontend
      desingn and to create attractive UI.
    </p>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe recusandae
      veritatis rerum magnam enim! Quisquam qui commodi dolore sequi impedit aut
      culpa quas architecto eligendi blanditiis deserunt sunt cum ex porro est
      eos, similique ut ab repellat id delectus? Enim quis vero iure commodi
      soluta, at itaque doloremque doloribus rem! Mollitia saepe perferendis
      distinctio voluptates sunt molestiae vero excepturi explicabo! Dolores
      porro debitis voluptate totam enim incidunt atque labore, culpa
      exercitationem unde maiores, quis sapiente assumenda reiciendis quod
      laudantium dolore nemo. Ipsum similique perferendis eius quod accusamus
      amet iusto reiciendis explicabo adipisci, provident mollitia praesentium
      tenetur, ea odio vero aliquid esse quasi rerum eligendi, enim ipsa culpa
      tempore dolorum repellat! Sunt, voluptas. Dolor accusantium facilis
      excepturi dolore quidem omnis alias consequatur id minima saepe cumque
      harum ut quisquam, sint ipsam quasi ad iste quos adipisci iusto tempora
      iure! In saepe iste praesentium esse natus eligendi. Labore iure quod
      neque, dolore dicta qui illum id exercitationem veritatis tempora sunt
      praesentium perferendis sed, explicabo ut atque eos. Porro eligendi
      laborum iure illo et dolores nihil necessitatibus quia consequuntur,
      quibusdam ea delectus asperiores maxime reprehenderit iusto voluptate in
      quod dolorem autem provident neque recusandae! Ex commodi necessitatibus
    </p>
  </div>
  <div class="even" id="skills">
    <h1>Skills</h1>
    <div class="skills">
      <div>HTML</div>
      <div>CSS</div>
      <div>JavaScript</div>
    </div>
  </div>
</template>
<script></script>
<style scoped>
.odd {
  background-color: #ffff;
  padding: 1rem;
  margin: 0px 1rem;
}
.even {
  color: white;
  padding: 1rem;
  margin: 0px 1rem;
}
div h1 {
  font-size: 2rem;
  text-decoration: underline;
  padding: 1rem;
}
div p {
  padding: 1rem;
  font-size: 20px;
}
.skills {
  display: flex;
  justify-content: space-around;
  height: 200px;
}
.skills div {
  display: flex;
  width: 200px;
  background-color: white;
  color: black;
  font-size: 45px;
  border-radius: 50%;
  align-items: center;
  justify-content: center;
}
@media screen and (max-width: 830px) {
  .skills {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    height: auto;
  }
  .skills div {
    height: 100px;
    width: 100px;
    font-size: 20px;
  }
}
</style>
