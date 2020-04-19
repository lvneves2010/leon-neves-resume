<template>
  <div id="Profile">
      <h1 style="font-size: 2rem;
      font-weight: 400;
      line-height: 2.5rem;
      letter-spacing: 0;
      padding-bottom: 15px;
      text-align: start;">Profile</h1>
     <cv-list>
      <cv-list-item>
        Professional with over 20 years experience on development & management of state-of-the-art Technologies ranging from services in the digital media industry (such as  Playstation 2 & 3) up to system development for Financial groups(Bradesco financeira) & health care Institutions;   
      </cv-list-item>
      <cv-list-item>
        Project management using Agile (SCRUM) methods & Framework ITIL v3;
      </cv-list-item>
      <cv-list-item>
        Relevant experience in web development (e-commerce & institutional platforms),SPAs, CRUDs, CMS, APIs (REST) & portfolios;
      </cv-list-item>
      <cv-list-item>
        Programming languages : Python 3, PHP, Javascript, Ruby, Typescript, Dart & C#;
      </cv-list-item>
      <cv-list-item>
        Frameworks e IDEs:
        Angular 2+, React & Vue; Node JS, Rails 5, ASP.NET (Core & MVC), Django, JQuery, PyCharm, Eclipse & GeneXus; Ionic React Native & Flutter;
      </cv-list-item>
      <cv-list-item>
        Style & webdesign tools: Materialize, Material Design, Bootstrap & Carbon; Sass & Less; Adobe Fireworks & Photoshop;
      </cv-list-item>
      <cv-list-item>
        Database SQL construction & maintenance tools: MySQL, cPanel, DB2, PostgreSQL, PHPmyAdmin, SQLite & MSSQL Server; ORM techniques Django & Entity Framework ( .NET ) & NoSQL database with MongoDB & Cloudant; 
      </cv-list-item>
      <cv-list-item>
        DevOps Management tools: Docker & Cloud Foundry; Kubernetes & Swarm;
      </cv-list-item>
    </cv-list>
  </div>
</template>
<script>
export default {
    name:"Profile"
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