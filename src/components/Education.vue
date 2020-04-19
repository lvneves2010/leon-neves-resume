<template>
  <div id="Education">
    <h1 style="font-size: 2rem;
      font-weight: 400;
      line-height: 2.5rem;
      letter-spacing: 0;
      padding-bottom: 15px;
      text-align: start;">Education</h1>
    <cv-list>
      <p>Degrees</p>
      <cv-list-item>
        UNIVESP (UNIVERSIDADE VIRTUAL DO ESTADO DE SÃO PAULO) - Computer engineering – current 2017/2022;
      </cv-list-item>
      <cv-list-item>
        UNIP – Bachelor of Business Administration – 2007 / 2010;
      </cv-list-item>
      <cv-list-item>
        E.T.E. Horacio Augusto da Silveira – Electronics Technician – completion in 1994
      </cv-list-item>
    </cv-list>
    <cv-list>
      <p>Certifications</p>
      <cv-list-item>
        Python & Django with Visual Studio 2017– Microsoft Virtual Academy (2019);  
      </cv-list-item>
      <cv-list-item>
        ASP.NET Core 2.0 (Begginer – Intermediate – Advanced) - Microsoft Virtual Academy (2019);
      </cv-list-item>
      <cv-list-item>
        ITIL v3 – Fundação Bradesco – (2018);
      </cv-list-item>
      <cv-list-item>
        Project management – Veduca – USP – (2018);
      </cv-list-item>
      <cv-list-item>
        Team management –FM2S – (2018);
      </cv-list-item>
      <cv-list-item>
        SCRUM fundamentals (SFC) – UDEMY (2018);
      </cv-list-item>
      <cv-list-item>
        ASP.NET MVC 5 – Microsoft Virtual Academy (2018); 
      </cv-list-item>
      <cv-list-item>
        Python 3 Complete – UDEMY (2018);
      </cv-list-item>
      <cv-list-item>
        Rails 5, Angular6, NativeScript – UDEMY (2018);
      </cv-list-item>
      <cv-list-item>
        Databases for Developers – Oracle (2018);
      </cv-list-item>
      <cv-list-item>
        Complete Webmaster Front-End –Danki Code (2018);
      </cv-list-item>
      <cv-list-item>
        <cv-link href="https://www.youracclaim.com/users/leonardo-neves.6260e18d/badges">
        IBM Acclaim certifications
      </cv-link>
      </cv-list-item>
    </cv-list>
  </div>
</template>
<script>
export default {
    name:"Education"
};
</script>
<style>
#Education {
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
  #Education {
    display: block;
  }
}
.cv-list {
    padding: 25px;
}
</style>