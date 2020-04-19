<template>
  <div id="Profile">
    <h1 v-if="!portugues"
      style="font-size: 2rem;
      font-weight: 400;
      line-height: 2.5rem;
      letter-spacing: 0;
      padding-bottom: 15px;
      text-align: start;"
    >Profile</h1>
    <h1 v-else
      style="font-size: 2rem;
      font-weight: 400;
      line-height: 2.5rem;
      letter-spacing: 0;
      padding-bottom: 15px;
      text-align: start;"
    >Perfil</h1>
    <cv-list v-if="!portugues">
      <cv-list-item>Professional with over 20 years experience on development & management of state-of-the-art Technologies ranging from services in the digital media industry (such as Playstation 2 & 3) up to system development for Financial groups(Bradesco financeira) & health care Institutions;</cv-list-item>
      <cv-list-item>Project management using Agile (SCRUM) methods & Framework ITIL v3;</cv-list-item>
      <cv-list-item>Relevant experience in web development (e-commerce & institutional platforms),SPAs, CRUDs, CMS, APIs (REST) & portfolios;</cv-list-item>
      <cv-list-item>Programming languages : Python 3, PHP, Javascript, Ruby, Typescript, Dart & C#;</cv-list-item>
      <cv-list-item>
        Frameworks & IDEs:
        Angular 2+, React & Vue; Node JS, Rails 5, ASP.NET (Core & MVC), Django, JQuery, PyCharm, Eclipse & GeneXus; Ionic React Native & Flutter;
      </cv-list-item>
      <cv-list-item>Style & webdesign tools: Materialize, Material Design, Bootstrap & Carbon; Sass & Less; Adobe Fireworks & Photoshop;</cv-list-item>
      <cv-list-item>Database SQL construction & maintenance tools: MySQL, cPanel, DB2, PostgreSQL, PHPmyAdmin, SQLite & MSSQL Server; ORM techniques Django & Entity Framework ( .NET ) & NoSQL database with MongoDB & Cloudant;</cv-list-item>
      <cv-list-item>DevOps Management tools: Docker & Cloud Foundry; Kubernetes & Swarm;</cv-list-item>
    </cv-list>
    <cv-list v-else>
      <cv-list-item>Profissional com mais de 20 anos de experiência desenvolvendo e gerenciando Tecnologias de vanguarda desde serviços para indústria de mídias óticas (como Playstation 2 e 3) até o desenvolvimento de sistemas para instituições financeiras (Bradesco financeira) e sistemas de saúde;</cv-list-item>
      <cv-list-item>Gerenciamento de projetos utilizando métodos Agile (SCRUM) e Framework ITIL v3;</cv-list-item>
      <cv-list-item>Experiência relevante em desenvolvimento web (e-commerce e plataformas institucionais), SPAs, CRUDs, CMS, APIs (REST) e portfolios;</cv-list-item>
      <cv-list-item>Linguagens de Programação : Python 3, PHP, Javascript, Ruby, Typescript, Dart & C#;</cv-list-item>
      <cv-list-item>
        Frameworks e IDEs:
        Angular 2+, React & Vue; Node JS, Rails 5, ASP.NET (Core & MVC), Django, JQuery, PyCharm, Eclipse & GeneXus; Ionic React Native & Flutter;
      </cv-list-item>
      <cv-list-item>Ferramentas de estilização & webdesign: Materialize, Material Design, Bootstrap & Carbon; Sass & Less; Adobe Fireworks & Photoshop;</cv-list-item>
      <cv-list-item>Ferramentas de manutenção e construção de Base de dados: SQL com MySQL, cPanel, DB2, PostgreSQL, PHPmyAdmin, SQLite & MSSQL Server; ORM com Django & Entity Framework ( .NET ) & NoSQL database com MongoDB & Cloudant;</cv-list-item>
      <cv-list-item>Ferramentas DevOps: Docker & Cloud Foundry; Kubernetes & Swarm;</cv-list-item>
    </cv-list>
  </div>
</template>
<script>
export default {
  name: "Profile",
  props: {
    portugues: {
      type: Boolean
    }
  }
};
</script>
<style>
#Profile {
  display: flex;
  justify-content: center;
  margin: 10px;
  padding-top: 15px;
  border-bottom-style: solid;
  border-bottom-color: black;
  border-bottom-width: 0.5px;
  padding-bottom: 15px;
}
@media screen and (max-width: 900px) {
  #Profile {
    display: block;
  }
}
</style>