<template>
  <div id="Experience">
    <h1 v-if="!portugues"
      style="font-size: 2rem;
    font-weight: 400;
    line-height: 2.5rem;
    letter-spacing: 0;
    padding-bottom: 15px;
    text-align: start;"
    >Professional History</h1>
    <h1 v-else
      style="font-size: 2rem;
    font-weight: 400;
    line-height: 2.5rem;
    letter-spacing: 0;
    padding-bottom: 15px;
    text-align: start;"
    >Histórico Profissional</h1>
    <cv-list v-if="!portugues">
      <cv-list-item>Application Developer – IBM – São Paulo – SP – May 2019 – Actual;</cv-list-item>
      <cv-list-item>Programming Analyst – 2Z soluções – São Paulo – SP – July 2018 – May 2019;</cv-list-item>
      <cv-list-item>Angular Developer – Scopus Soluções em TI – SP – September 2018 – March 2019;</cv-list-item>
      <cv-list-item>Technical consultancy – HSI – Guarulhos – SP – June 2013 – September 2018;</cv-list-item>
      <cv-list-item>Commercial director – Symcon Latin – São Jose dos Campos – SP – Oct/2010 – May 2013</cv-list-item>
      <cv-list-item>Technical manager – Sony DADC – Manaus – AM – Mar/2008 – Sep/2010</cv-list-item>
      <cv-list-item>Industrial manager – Nordeste Digital Line/CD+ – Fortaleza – CE – Jul/2006 – Jan/2008</cv-list-item>
      <cv-list-item>Service Technician – Toolex/Singulus – Rio de Janeiro/Eindhoven – Nov/1999 – Mar/2006</cv-list-item>
      <cv-list-item>Mastering Technician – Novodisc Brasil – Apr/1998 – Set/1999</cv-list-item>
      <cv-list-item>Mastering Technician – Videolar Multimídia – Feb/1995 – Feb/1998</cv-list-item>
    </cv-list>
    <cv-list v-else>
      <cv-list-item>Desenvolvedor de Aplicações – IBM – São Paulo – SP – Maio 2019 - Presente;</cv-list-item>
      <cv-list-item>Analista de Programação – 2Z soluções – São Paulo – SP – Julho 2018 – Maio 2019;</cv-list-item>
      <cv-list-item>Desenvolvedor Angular – Scopus Soluções em TI – SP – Setembro 2018 – Março 2019;</cv-list-item>
      <cv-list-item>Consultoria Técnica – HSI – Guarulhos – SP – Junho 2013 – Maio 2019;</cv-list-item>
      <cv-list-item>Diretor Comercial – Symcon Latin – São Jose dos Campos – SP – Outubro 2010 – Maio 2013;</cv-list-item>
      <cv-list-item>Gerente Técnico  – Sony DADC – Manaus – AM – Março 2008 – Setembro 2010;</cv-list-item>
      <cv-list-item>Gerente Industrial – Nordeste Digital Line/CD+ – Fortaleza – CE – Julho 2006 – Janeiro 2008;</cv-list-item>
      <cv-list-item>Técnico de Serviços – Toolex/Singulus – Rio de Janeiro/Eindhoven – Novembro 1999 – Março  2006;</cv-list-item>
      <cv-list-item>Técnico de Masterização – Novodisc Brasil – Abril 1998 – Setembro  1999;</cv-list-item>
      <cv-list-item>Técnico de Masterização – Videolar Multimídia – Fevereiro 1995 – Fevereiro 1998;</cv-list-item>
    </cv-list>
  </div>
</template>
<script>
export default {
  name: "Education",
  props: {
    portugues: {
      type: Boolean
    }
  }
};
</script>
<style>
#Experience {
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
  #Experience {
    display: block;
  }
}
</style>