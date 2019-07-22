<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
<script src="https://unpkg.com/scrollnav@3.0.1/dist/scrollnav.min.umd.js"></script>

<style>

/* left */
h2 + aside {
    color: grey;
    width: 30%;
    background-color: white;
    top: 50%;
    position: sticky;
    float: left;
    font-size: 1rem;
    margin-top: 80%;
    margin-left: -50%;
}

/* right */
h3, h3 + * {
    /* margin-left: 30%; */
}

.container {
  display: flex;
}

.left {
  width: 20%;
  min-width: 250px;
  padding: 0rem;
  margin-top: 2rem;
  z-index: 9999999;
}

.right {
  flex: 1;
  padding-left: 3rem;
}

nav {
  position: sticky;
  top: 5rem;
}

nav.scroll-nav {}

ol.scroll-nav__list {}

li.scroll-nav__item.scroll-nav__item--active,
li.scroll-nav__item.scroll-nav__item--active a.scroll-nav__link {
  font-weight: bold;
  }
      
a.scroll-nav__link {}

</style>

<div class="container">
<div class="left"></div>
<div class="right">

## asdfasdfasd

<aside>

 - A smattering of academic and industry best practices
 - Understand what a p-value is and is not, p-hacking and False Discovery Rate, Type 1 vs. Type 2 errors, sample size calculation
 - Understand the pros and cons of t-tests/p-value/NHST-based testing frameworks and alternatives

</aside>

### Philosophy/Culture

1. [So You Think You Can Test? (Simulation game by Lukas Vermeer)](http://lukasvermeer.github.io/confidence/): Read the instructions and play a few rounds in simulation mode
     - Magna occaecat voluptate proident excepteur tempor ullamco dolor sit voluptate deserunt enim irure ullamco.
     - Magna occaecat voluptate proident excepteur tempor ullamco dolor sit voluptate deserunt enim irure ullamco.

2. [Please, Please Don’t A/B Test That](https://patreonhq.com/please-please-dont-a-b-test-that-980a9630e4fb) 
3. [The art of A/B testing](https://towardsdatascience.com/the-art-of-a-b-testing-5a10c9bb70a4)
4. [Democratizing online controlled experiments at Booking.com](https://arxiv.org/abs/1710.08217)

### Experimental Design
1. [Getting Past Statistical Significance: Foundations of AB Testing and Experimentation](https://conductrics.com/PastStatisticalSignificance)
1. [Guidelines for A/B Testing](https://hookedondata.org/guidelines-for-ab-testing/) 
1. [How Not To Run an A/B Test](http://www.evanmiller.org/how-not-to-run-an-ab-test.html)
1. [A/B Testing Rigorously (without losing your job)](http://elem.com/~btilly/ab-testing-multiple-looks/part1-rigorous.html)
1. [Chasing Statistical Ghosts in Experimentation](https://towardsdatascience.com/chasing-statistical-ghosts-in-experimentation-3f393323a1c1) (3-part series):
    1. [The first Ghost of Experimentation: It’s either significant or noise](https://towardsdatascience.com/the-first-ghost-of-experimentation-its-either-significant-or-noise-b897e3058655)
    1. [The second Ghost of Experimentation: The fallacy of session based metrics](https://towardsdatascience.com/the-second-ghost-of-experimentation-the-fallacy-of-session-based-metrics-fb65006d30ff)
    1. [The third Ghost of Experimentation: Multiple comparisons](https://towardsdatascience.com/the-third-ghost-of-experimentation-multiple-comparisons-65af360169a1)
1. [Leaky Abstractions In Online Experimentation Platforms: Categorising Common Challenges](https://booking.ai/leaky-abstractions-in-online-experimentation-platforms-ae4cf05013f9): How things go awry in online A/B testing
1. [‘Good jobs’ vs. ‘jobs’: Survey experiments can measure the effects of question wording – and more (Pew Research Center, 2019)](http://www.pewresearch.org/fact-tank/2019/01/29/good-jobs-vs-jobs-survey-experiments-can-measure-the-effects-of-question-wording-and-more/)
1. [Head, K. & Harsin, A. (2017). Quasi-experimental design. In M. Allen (Ed.), The sage encyclopedia of communication research methods (pp. 1384-1387). Thousand Oaks, CA: SAGE Publications, Inc doi: 10.4135/9781483381411.n478](./resources/head2018_quasiexp.pdf): Overview of quasi-experimental designs
1. [Experiments at Airbnb](https://medium.com/airbnb-engineering/experiments-at-airbnb-e2db3abf39e7)


## j;lkj;lkj;lkj;lkj;lk

<aside>

 - A smattering of academic and industry best practices
 - Understand what a p-value is and is not, p-hacking and False Discovery Rate, Type 1 vs. Type 2 errors, sample size calculation
 - Understand the pros and cons of t-tests/p-value/NHST-based testing frameworks and alternatives
 - 
</aside>

### Philosophy/Culture

1. [So You Think You Can Test? (Simulation game by Lukas Vermeer)](http://lukasvermeer.github.io/confidence/): Read the instructions and play a few rounds in simulation mode
     - Magna occaecat voluptate proident excepteur tempor ullamco dolor sit voluptate deserunt enim irure ullamco.
     - Magna occaecat voluptate proident excepteur tempor ullamco dolor sit voluptate deserunt enim irure ullamco.

2. [Please, Please Don’t A/B Test That](https://patreonhq.com/please-please-dont-a-b-test-that-980a9630e4fb) 
3. [The art of A/B testing](https://towardsdatascience.com/the-art-of-a-b-testing-5a10c9bb70a4)
4. [Democratizing online controlled experiments at Booking.com](https://arxiv.org/abs/1710.08217)

### Experimental Design
1. [Getting Past Statistical Significance: Foundations of AB Testing and Experimentation](https://conductrics.com/PastStatisticalSignificance)
1. [Guidelines for A/B Testing](https://hookedondata.org/guidelines-for-ab-testing/) 
1. [How Not To Run an A/B Test](http://www.evanmiller.org/how-not-to-run-an-ab-test.html)
1. [A/B Testing Rigorously (without losing your job)](http://elem.com/~btilly/ab-testing-multiple-looks/part1-rigorous.html)
1. [Chasing Statistical Ghosts in Experimentation](https://towardsdatascience.com/chasing-statistical-ghosts-in-experimentation-3f393323a1c1) (3-part series):
    1. [The first Ghost of Experimentation: It’s either significant or noise](https://towardsdatascience.com/the-first-ghost-of-experimentation-its-either-significant-or-noise-b897e3058655)
    1. [The second Ghost of Experimentation: The fallacy of session based metrics](https://towardsdatascience.com/the-second-ghost-of-experimentation-the-fallacy-of-session-based-metrics-fb65006d30ff)
    1. [The third Ghost of Experimentation: Multiple comparisons](https://towardsdatascience.com/the-third-ghost-of-experimentation-multiple-comparisons-65af360169a1)
1. [Leaky Abstractions In Online Experimentation Platforms: Categorising Common Challenges](https://booking.ai/leaky-abstractions-in-online-experimentation-platforms-ae4cf05013f9): How things go awry in online A/B testing
1. [‘Good jobs’ vs. ‘jobs’: Survey experiments can measure the effects of question wording – and more (Pew Research Center, 2019)](http://www.pewresearch.org/fact-tank/2019/01/29/good-jobs-vs-jobs-survey-experiments-can-measure-the-effects-of-question-wording-and-more/)
1. [Head, K. & Harsin, A. (2017). Quasi-experimental design. In M. Allen (Ed.), The sage encyclopedia of communication research methods (pp. 1384-1387). Thousand Oaks, CA: SAGE Publications, Inc doi: 10.4135/9781483381411.n478](./resources/head2018_quasiexp.pdf): Overview of quasi-experimental designs
1. [Experiments at Airbnb](https://medium.com/airbnb-engineering/experiments-at-airbnb-e2db3abf39e7)


## Experimentation, a;lkds jf, asdkjf a;lds, losngd;las jd;lfja;lsd

<aside>

 - A smattering of academic and industry best practices
 - Understand what a p-value is and is not, p-hacking and False Discovery Rate, Type 1 vs. Type 2 errors, sample size calculation
 - Understand the pros and cons of t-tests/p-value/NHST-based testing frameworks and alternatives
 - 
</aside>

### Philosophy/Culture

1. [So You Think You Can Test? (Simulation game by Lukas Vermeer)](http://lukasvermeer.github.io/confidence/): Read the instructions and play a few rounds in simulation mode
     - Magna occaecat voluptate proident excepteur tempor ullamco dolor sit voluptate deserunt enim irure ullamco.
     - Magna occaecat voluptate proident excepteur tempor ullamco dolor sit voluptate deserunt enim irure ullamco.

2. [Please, Please Don’t A/B Test That](https://patreonhq.com/please-please-dont-a-b-test-that-980a9630e4fb) 
3. [The art of A/B testing](https://towardsdatascience.com/the-art-of-a-b-testing-5a10c9bb70a4)
4. [Democratizing online controlled experiments at Booking.com](https://arxiv.org/abs/1710.08217)

### Experimental Design
1. [Getting Past Statistical Significance: Foundations of AB Testing and Experimentation](https://conductrics.com/PastStatisticalSignificance)
1. [Guidelines for A/B Testing](https://hookedondata.org/guidelines-for-ab-testing/) 
1. [How Not To Run an A/B Test](http://www.evanmiller.org/how-not-to-run-an-ab-test.html)
1. [A/B Testing Rigorously (without losing your job)](http://elem.com/~btilly/ab-testing-multiple-looks/part1-rigorous.html)
1. [Chasing Statistical Ghosts in Experimentation](https://towardsdatascience.com/chasing-statistical-ghosts-in-experimentation-3f393323a1c1) (3-part series):
    1. [The first Ghost of Experimentation: It’s either significant or noise](https://towardsdatascience.com/the-first-ghost-of-experimentation-its-either-significant-or-noise-b897e3058655)
    1. [The second Ghost of Experimentation: The fallacy of session based metrics](https://towardsdatascience.com/the-second-ghost-of-experimentation-the-fallacy-of-session-based-metrics-fb65006d30ff)
    1. [The third Ghost of Experimentation: Multiple comparisons](https://towardsdatascience.com/the-third-ghost-of-experimentation-multiple-comparisons-65af360169a1)
1. [Leaky Abstractions In Online Experimentation Platforms: Categorising Common Challenges](https://booking.ai/leaky-abstractions-in-online-experimentation-platforms-ae4cf05013f9): How things go awry in online A/B testing
1. [‘Good jobs’ vs. ‘jobs’: Survey experiments can measure the effects of question wording – and more (Pew Research Center, 2019)](http://www.pewresearch.org/fact-tank/2019/01/29/good-jobs-vs-jobs-survey-experiments-can-measure-the-effects-of-question-wording-and-more/)
1. [Head, K. & Harsin, A. (2017). Quasi-experimental design. In M. Allen (Ed.), The sage encyclopedia of communication research methods (pp. 1384-1387). Thousand Oaks, CA: SAGE Publications, Inc doi: 10.4135/9781483381411.n478](./resources/head2018_quasiexp.pdf): Overview of quasi-experimental designs
1. [Experiments at Airbnb](https://medium.com/airbnb-engineering/experiments-at-airbnb-e2db3abf39e7)

</div>
</div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/showdown/1.9.0/showdown.min.js"></script>

<script>
// showdown.js
var text = document.querySelector('.right').innerHTML;
converter = new showdown.Converter(); 
document.querySelector('.right').innerHTML = converter.makeHtml(text);

// scrollnav.js
const content = document.querySelector('.right');
const insertTarget = document.querySelector('.left');
scrollnav.init(content, { 
  debug: false,
  insertTarget: insertTarget,
  insertLocation: 'append'
  });
</script>