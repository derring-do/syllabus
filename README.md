<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
<script src="https://unpkg.com/scrollnav@3.0.1/dist/scrollnav.min.umd.js"></script>

<style>

:root {
  --nav-link-color: grey; 
}

.right li {
  padding-bottom: .5rem;
}

.right a {
  color: #614db3 !important;
}

.right a:hover {
  color: #7300e6 !important;
}

.right a:active, a:visited {
  color: #400080 !important;
}

h2 {
  text-transform: uppercase; 
  padding: 1rem 0 1rem 0;
}

/* sticky asides */
aside {
    color: grey;
    width: 20%;
    background-color: white;
    top: 5rem;
    position: sticky;
    float: right;
    font-size: .8rem;
    /* margin-top: 50%; */
    margin-right: -25%;
    height: 30%;
    font-style: italic;
    font-family: serif;
    padding-left: 1rem;
}

aside:before {
  content: "                                                   \A";
  white-space: pre;
  border-top: 1px solid grey;
}

aside ul {
  padding-left: 1rem;
}

/* scrollnav.js stuff */
.container {
  display: flex;
  padding: 0rem;
  margin: 0rem;
  flex-wrap: wrap;
  font-size: 1.05rem;
}

.left {
  width: 25%;
  min-width: 300px;
  padding: 0rem;
  margin-top: 2rem;
}

.right {
  flex: 1;
  padding-left: 3rem;
}

nav {
  position: sticky;
  top: 5rem;
  font-size: 1rem;
  line-height: 1.7rem;
  color: var(--nav-link-color) !important;
}

nav * a {
  color: var(--nav-link-color) !important;
}

nav.scroll-nav {}

ol.scroll-nav__list {}

li.scroll-nav__item.scroll-nav__item--active,
li.scroll-nav__item.scroll-nav__item--active a.scroll-nav__link,
li.scroll-nav__sub-item.scroll-nav__item--active a.scroll-nav__sub-link {
  font-weight: bold;
  }
      
a.scroll-nav__link {}

</style>

<div class="container">
<div class="left"></div>
<div class="right">

General introductory text to online social research: *Bit by bit: social research in the digital age.* 2018. Salganik, Matthew J. Chapters are concise and accessible with mathematical notes and "What to Read Next" references and exercises at end. The platform also has Hypothesis embedded, which is a [generally useful plugin for all-purpose/cross-Internet annotation. (free account required)](https://web.hypothes.is/start/)
  
[Read online](https://www.bitbybitbook.com/en/1st-ed/preface) or [request hard copy from Harvard Library](http://id.lib.harvard.edu/alma/990152301880203941/catalog). 
- [2.3 Ten common characteristics of big data](https://www.bitbybitbook.com/en/1st-ed/observing-behavior/characteristics/)
- [2.4 Research strategies](https://www.bitbybitbook.com/en/1st-ed/observing-behavior/strategies/)
- [3 Asking Questions](https://www.bitbybitbook.com/en/1st-ed/asking-questions/)
- [4 Running Experiments](https://www.bitbybitbook.com/en/1st-ed/running-experiments/)
- [6 Ethics](https://www.bitbybitbook.com/en/1st-ed/ethics/)

## Experimentation

<aside>

- A smattering of academic and industry best practices
- Understand what a p-value is and is not, p-hacking and False Discovery Rate, Type 1 vs. Type 2 errors, sample size calculation
- Understand the pros and cons of t-tests/p-value/NHST-based testing frameworks and alternatives

</aside>

### Philosophy/Culture
1. [So You Think You Can Test? (Simulation game by Lukas Vermeer)](http://lukasvermeer.github.io/confidence/): Read the instructions and play a few rounds in simulation mode
2. [Please, Please Don’t A/B Test That](https://patreonhq.com/please-please-dont-a-b-test-that-980a9630e4fb) 
3. [The art of A/B testing](https://towardsdatascience.com/the-art-of-a-b-testing-5a10c9bb70a4)
4. [Democratizing online controlled experiments at Booking.com](https://arxiv.org/abs/1710.08217)

### Experimental Design
1. [A/B Testing and Beyond: Designed Experiments for Data Scientists (The University of San Francisco's Data Institute)](usf_ab_testing_and_beyond.pdf)
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
1. Head, K. & Harsin, A. (2017). Quasi-experimental design. In M. Allen (Ed.), The sage encyclopedia of communication research methods (pp. 1384-1387). Thousand Oaks, CA: SAGE Publications, Inc doi: 10.4135/9781483381411.n478: [link](./resources/head2018_quasiexp.pdf): Overview of quasi-experimental designs
1. [Experiments at Airbnb](https://medium.com/airbnb-engineering/experiments-at-airbnb-e2db3abf39e7)
1. [Detecting Interference: An A/B Test of A/B Tests](https://engineering.linkedin.com/blog/2019/06/detecting-interference--an-a-b-test-of-a-b-tests)
1. [Understanding Experimentation Platforms](OReilly_Understanding_Experimentation_Platforms.pdf): Optimizely white paper 

### T-Test/p-value/NHST Discontents and Alternatives
1. [When the Revolution Came for Amy Cuddy](https://www.nytimes.com/2017/10/18/magazine/when-the-revolution-came-for-amy-cuddy.html)
    - "As a young social psychologist, she played by the rules and won big: an influential study, a viral TED talk, a prestigious job at Harvard. Then, suddenly, the rules changed."
  
1. [Suffering from a Non-inferiority Complex?](https://multithreaded.stitchfix.com/blog/2019/05/06/noninferiority/): Good, simplified examples and illustrations
   - "Seaching 80% of your room for your backpack is a bit like performing a test with 80% power. If you don't find your backpack after searching only 80% of the room, should you conclude the backpack is not in your room?"
1. [How Etsy Handles Peeking in A/B Testing](https://codeascraft.com/2018/10/03/how-etsy-handles-peeking-in-a-b-testing/)
1. Berman, Ron and Pekelis, Leonid and Scott, Aisling and Van den Bulte, Christophe, p-Hacking and False Discovery in A/B Testing (December 11, 2018). Available at SSRN: https://ssrn.com/abstract=3204791 or http://dx.doi.org/10.2139/ssrn.3204791
1. [Non-Inferiority Designs in A/B Testing](https://www.analytics-toolkit.com/whitepapers.php?paper=non-inferiority-designs-ab-testing)
1. [Alternatives to the Randomized Controlled Trial](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2446460/)
1. Walker, E., & Nowacki, A. S. (2010). Understanding equivalence and noninferiority testing. Journal of general internal medicine, 26(2), 192–196. doi:10.1007/s11606-010-1513-8: [link](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3019319/)
1. [Reducing A/B test measurement variance by 30%+ (TripAdvisor)](https://www.tripadvisor.com/engineering/reducing-a-b-test-measurement-variance-by-30/)
1.  [How Booking.com increases the power of online experiments with CUPED](https://booking.ai/how-booking-com-increases-the-power-of-online-experiments-with-cuped-995d186fff1d)

### General Stats Refreshers/References
1. [Statistics for people in a hurry](https://towardsdatascience.com/statistics-for-people-in-a-hurry-a9613c0ed0b)
1. [Glossary of Statistical Terms (Frank Harrell)](./resources/harrell2019_glossary_stats.pdf)
1. [StatQuest](https://statquest.org/video-index/): Videos
1. [Causal Inference Animated Plots](http://nickchk.com/causalgraphs.html): This outlines some non-experimental designs and methods to visualize relationships in situations where a randomized control experiment isn't feasible. 
1. The Book of Why: The New Science of Cause and Effect. 2018. Judea Pearl and Dana Mackenzie: Gives historical context to why the language of frequentist hypothesis testing seems so constrained re: causal claims.
    1. [Chapter 1: The Ladder of Causation](http://bayes.cs.ucla.edu/WHY/why-ch1.pdf)
    1. [Chapter 2. From Buccaneers to Guinea Pigs: The Genesis of Causal Inference](http://bayes.cs.ucla.edu/WHY/why-ch2.pdf)
1. [Andrew Gelman's Applied Regression exam questions and answers](https://statmodeling.stat.columbia.edu/?s=%22applied+regression+final+exam%22)

## Digital Analytics

<aside>
None of that prepared him for the arena, the crowd, the tense hush, the towering puppets of light from a half-open service hatch framed a heap of discarded fiber optics and the robot gardener. No light but the muted purring of the console in faded pinks and yellows.
</aside>

1. [A Beginner’s Guide to Adobe Analytics](https://www.seerinteractive.com/blog/a-beginners-guide-to-adobe-analytics/)
2. [The Definitive Guide to Adobe Analysis Workspace](https://www.seerinteractive.com/blog/the-definitive-guide-to-adobe-analysis-workspace/)
3. [Why (and why not) use a Data Layer?](https://www.digitaldatatactics.com/index.php/2016/09/07/why-and-why-not-use-a-data-layer/)
4. [Adobe’s performanceTiming plugin, with some improvements and an explanation](https://33sticks.com/adobes-performancetiming-plugin-improvements-explanation/)
5. [33 Tangents – Episode #29 – Publishing Analytics with Todd Schauman of The Christian Science Monitor](https://33sticks.com/33-tangents-episode-29-publishing-analytics-todd-schauman-the-christian-science-monitor/) (50 min)
6. [Digital Analytics Power Hour podcast](http://www.analyticshour.io/all-podcast-episodes/): Most episodes have transcripts. I'd just work your way through most of their catalog over the next six months -- make note of episodes that are particularly helpful or surprisingly not, and we can add them here.
7. Neumann, Nico and Tucker, Catherine E. and Whitfield, Timothy, How Effective Is Black-box Digital Consumer Profiling and Audience Delivery?: Evidence from Field Studies (June 25, 2018). Available at SSRN: https://ssrn.com/abstract=3203131 or http://dx.doi.org/10.2139/ssrn.3203131: [link](./resources/neumann2018_consumer_profile.pdf): This is about buying third-party data from brokers, but provides a good overview of the digital tracking technology in general
8. [#measure Slack](): free community for people working in digital analytics, broadly defined; includes channels for specific Adobe products, general data science, R and statistics, Google Analytics, testing methodology, etc. Must submit form to receive invitation.

## Surveys

<aside>

Understand survey design principles for mitigating response biases

Understand margin of error and be able to estimate it for a given survey

</aside>
****
### Questionnaire Design
1. [Pew Research Center Methods 101 YouTube Playlist](https://www.youtube.com/playlist?list=PLZ9z-Af5ISavJpPlvdMU4T-etIDOUmldk): Currently 3 videos all ~5 min or less
2. [Harvard University Program on Survey Research](https://psr.iq.harvard.edu/book/guides-survey-research)
3. [Representative Samples: Does Sample Size Really Matter?](https://www.surveygizmo.com/resources/blog/representative-sample) 
4. [Margin of error](https://www.cs.mcgill.ca/~rwest/wikispeedia/wpcd/wp/m/Margin_of_error.htm)
5. [10 Best Practices in Survey Screening](https://www.researchnow.com/blog/10-best-practices-survey-screening/): Don't terminate respondents after sensitive demographic questions
6. [Yes, There is a Right and Wrong Way to Number Rating Scales (SurveyMonkey)](https://www.surveymonkey.com/mp/how-to-number-rating-scales/): Understand unipolar vs. bipolar scales
7. [How much do the numbers used in survey scales really matter?](https://medium.com/pew-research-center-decoded/how-much-do-the-numbers-used-in-survey-scales-really-matter-227d84ab2a13?source=rss----9ba5753f8834---4)
    - These outcomes suggest that when a scale is easily divided in half — for example, when the maximum value is 6 rather than 7 — it’s more likely for respondents to select the midpoint. Previous research has found that respondents are likely to assume that half the top endpoint is a scale’s midpoint, so when half the top endpoint is not an answer option (e.g., 3.5 on the 1–7 scale), respondents seeking the central point on the scale may sometime choose 3 (not the scale midpoint) and sometimes choose 4 (the actual scale midpoint). Those who received the 0–6 scale could more easily find the midpoint (3) by halving the top endpoint.
  
8. [Comparing Forced-Choice and Select-All Online Survey Responses - Pew Research Center Methods](https://www.pewresearch.org/methods/2019/05/09/when-online-survey-respondents-only-select-some-that-apply/)
   - The new study found compelling evidence that forced-choice questions yield more accurate results than select-all-that-apply lists. 
9.  [Survey rating scales: numbered vs worded lists (SurveyMonkey)](https://www.surveymonkey.com/mp/presenting-your-rating-scales-numbered-versus-worded-lists/)
10. [What is a Likert scale? (SurveyMonkey)](https://www.surveymonkey.com/mp/likert-scale/?ut_source1=mp&ut_source2=survey_guidelines)
11. [A survey resolution: Stop throwing away your variance! (SurveyMonkey)](https://www.surveymonkey.com/curiosity/methodology-variance/)
12. [What’s the best way to design a matrix question? (SurveyMonkey)](https://www.surveymonkey.com/curiosity/whats-best-way-design-matrix-question/)
13. [Let’s agree NOT to use agree/disagree questions (SurveyMonkey)](https://www.surveymonkey.com/curiosity/lets-agree-not-use-agreedisagree-questions/)
14. [Why (and how!) to ask survey questions on sexual orientation and gender identity (SurveyMonkey)](https://www.surveymonkey.com/curiosity/ask-survey-questions-sexual-orientation-gender-identity/)
15. Huang, Jason & Bowling, Nathan & Liu, Mengqiao & Li, Yuhui. (2014). Detecting Insufficient Effort Responding with an Infrequency Scale: Evaluating Validity and Participant Reactions. Journal of Business and Psychology. 10.1007/s10869-014-9357-6: [link](https://www.researchgate.net/publication/261597350_Detecting_Insufficient_Effort_Responding_with_an_Infrequency_Scale_Evaluating_Validity_and_Participant_Reactions): Understand what IER is, what it might look like, pros and cons of various countermeasures (longstring, psychometric antonym/synonym, Mahalanobis distance, manipulation/attention check)
    + [Cliffnotes version](https://github.com/SurveyMan/SurveyMan/wiki/Detecting-and-Deterring-Insufficient-Effort-Responding)
16. [Net Promoter Score Pros and Cons: Why Use NPS? (SurveyMonkey)](https://www.surveymonkey.com/mp/nps-pros-cons-why-use-nps/)
17. [Net Promoter Score (Wikipedia)](https://en.wikipedia.org/wiki/Net_Promoter)
18. [Respectful Collection of Demographic Data](https://medium.com/@anna.sarai.rosenberg/respectful-collection-of-demographic-data-56de9fcb80e2)
19. [SurveyMonkey's survey science blog](https://www.surveymonkey.com/curiosity/topic/survey-science/)
20. [Andrew Gelman's Design and Analysis of Sample Surveys exam questions and answers](https://statmodeling.stat.columbia.edu/?s=%22Design+and+Analysis+of+Sample+Surveys%22)
    
    -  "18. A survey is taken of 100 undergraduates, 100 graduate students, and 100 continuing education students at a university. Assume a simple random sample within each group. Each student is asked to rate his or her satisfaction (on a 1–10 scale) with his or her experiences. Write the estimate and standard error of the average satisfaction of all the students at the university. Introduce notation as necessary for all the information needed to solve the problem."

### Translation and Internationalization
1. [Questionnaire design and translation (Pew)](http://www.pewresearch.org/methods/international-survey-research/questionnaire-design-and-translation/)
1. [The Unique Challenges of Surveying U.S. Latinos (Pew)](http://www.pewresearch.org/methods/2015/11/12/the-unique-challenges-of-surveying-u-s-latinos/): 
1. Kleiner, B., Pan, Y., & Bouic, J. (2009). The Impact of Instructions on Survey Translation: An Experimental Study. Survey Research Methods, 3(3), 113-122. doi: http://dx.doi.org/10.18148/srm/2009.v3i3.1563: [link](./resources/instructions-survey-translations.pdf): Includes translator instructions template
1. [Gallup Worldwide Research Methodology and Codebook (2017)](./resources/gallup2017_worldwide_methodology.pdf)

### Panels/Recruiting
1. [ESOMAR 28 Questions to Help Research Buyers of Online Samples](https://www.esomar.org/uploads/public/knowledge-and-standards/documents/ESOMAR-28-Questions-to-Help-Buyers-of-Online-Samples-September-2012.pdf): Overview of terminology and considerations re: panel samples. Every reputable sample provider should have a document answering these questions. 
    + [Qualtrics's ESOMAR responses](https://success.qualtrics.com/rs/qualtrics/images/ESOMAR%2028%202014.pdf)
1. Anson, I. G. (2018). Taking the time? Explaining effortful participation among low-cost online survey participants. Research & Politics. https://doi.org/10.1177/2053168018785483: [link](https://journals.sagepub.com/doi/full/10.1177/2053168018785483#articleCitationDownloadContainer)

## Web Development, Privacy, and Security

<aside>

- Working knowledge of HTML, CSS, JavaScript, and other internet things for designing tests, debugging, customizing surveys and intercepts. 
- Understand how to navigate the DOM to select elements to change and make needed changes
- Understand our stylesheet and when/how to use/preserve existing helper classes, esp. for mobile breakpoints (e.g., hide-for-small vs. small-only)
- Write code that is slightly more efficient than your average bear to minimize burden on the site; faster site = less likely that what we observe is due to difference in site loading time. 
- Don't break the site
- 
</aside>

### Web Development
1. [How a webpage is loaded and displayed](https://varvy.com/pagespeed/display.html)
2. [Introduction to HTML](https://info474-s17.github.io/book/introduction-to-html.html)
3. [Introduction to CSS](https://info474-s17.github.io/book/introduction-to-css.html)
    - [CSS Diner](https://flukeout.github.io/): Interactive game to get used to CSS selectors
4. [Responsive CSS](https://info474-s17.github.io/book/responsive-css.html)
    - [Flexbox Froggy](https://flexboxfroggy.com/): Interactive game to understand the flex framework
5. [JavaScript](https://info474-s17.github.io/book/javascript.html)
6. [JavaScript control flow and error handling](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Control_flow_and_error_handling): Write code that breaks usefully 
7. JavaScript Regex:
    1. [Debuggex](https://www.debuggex.com/)
    2. [Regex101](https://regex101.com/)
8. 9. [Principles of Accessible and Universal Design](http://www.usabilityfirst.com/about-usability/accessibility/principles-of-accessible-and-universal-design/)
9.  More JavaScript:
Types, functions, loops/iterators, truthy/falsy, regex, IIFE/self-executing anonymous functions, DOM navigation
    + [Making Bookmarklets](https://gist.github.com/caseywatts/c0cec1f89ccdb8b469b1)
    + https://github.com/getify/You-Dont-Know-JS
    + https://www.digitalocean.com/community/tutorials/how-to-traverse-the-dom
    + [Notes on "Javascript: Understanding the Weird Parts"](https://github.com/tomquinonero/JSTheWeirdParts)
1. `document.designMode = 'on'`: [demo](https://twitter.com/imac2/status/1135875294156480512)

### Privacy
Web privacy technology and policies are evolving, and, with them, analytics platforms adapt with various levels of transparency. What we might observe as a steep decline in visitors might actually be attributable to new browser policies. Some primers:

1. [What Does Private Browsing Mode Do?](https://medium.com/@mshelton/what-does-private-browsing-mode-do-adfe5a70a8b1)
2. [GDPR](https://www.wired.co.uk/article/what-is-gdpr-uk-eu-legislation-compliance-summary-fines-2018)
3. [ITP 2.1 and Web Analytics](https://www.simoahava.com/analytics/itp-2-1-and-web-analytics/): Intelligent Tracking Prevention (ITP) is Apple's version of privacy features for Safari
4. [Google announces two new privacy-focused features for Chrome at the I/O 2019 developer conference](https://www.zdnet.com/article/google-chrome-to-support-same-site-cookies-get-anti-fingerprinting-protection/) 
5. [The nascent DETOUR ACT in Congress calls for data-collecting restrictions on websites with over 100 million active users](https://www.zdnet.com/article/senators-introduce-bill-to-ban-dark-patterns-on-big-tech-platforms/)

### Security
Generally, the site is up to date on the latest vulnerabilities, but when we write code for experiments or update (or fail to update) vendor libraries, we should try not to override any of the guardrails... Relevant topics from the [OWASP Cheat Sheet Series ("Life is too short -- AppSec is hard -- Cheat!")](https://cheatsheetseries.owasp.org/):

1. [Third Party Javascript](https://cheatsheetseries.owasp.org/cheatsheets/Third_Party_Javascript_Management_Cheat_Sheet.html)
2. [Session Management](https://cheatsheetseries.owasp.org/cheatsheets/Session_Management_Cheat_Sheet.html)
3. [Tabnabbing](https://cheatsheetseries.owasp.org/cheatsheets/HTML5_Security_Cheat_Sheet.html#tabnabbing)
4. [iFrames](https://cheatsheetseries.owasp.org/cheatsheets/HTML5_Security_Cheat_Sheet.html#sandboxed-frames)

## Data Analysis, Visualization, and Programming
Best practices for organizing and visualizing; tutorials for scripted languages

### Philosophy
1. [Tukey, Design Thinking, and Better Questions - Roger Peng](https://simplystatistics.org/2019/04/17/tukey-design-thinking-and-better-questions/) 
    - Corollary: Tukey, John W. The Future of Data Analysis. Ann. Math. Statist. 33 (1962), no. 1, 1--67. doi:10.1214/aoms/1177704711. https://projecteuclid.org/euclid.aoms/1177704711: [link](https://projecteuclid.org/download/pdf_1/euclid.aoms/1177704711)

### Management/Project Planning
1. [11 Tips for Improving Productivity using OneNote](https://medium.com/gitbit/10-tips-to-improve-productivity-using-onenote-85dee4a32cf2)
1. [How Data Scientists Think - A Mini Case Study](https://simplystatistics.org/2019/01/09/how-data-scientists-think-a-mini-case-study/)
1. [Wickham, H. (2014). Tidy Data. Journal of Statistical Software, 59(10), 1 - 23. doi:http://dx.doi.org/10.18637/jss.v059.i10](https://www.jstatsoft.org/article/view/v059i10): How to organize data 
1. [Data Organization in Spreadsheets](https://www.tandfonline.com/doi/full/10.1080/00031305.2017.1375989)
1. [Designing Projects](https://nicercode.github.io/blog/2013-04-05-projects/): directory layout example
1. [Markdown](https://info474-s17.github.io/book/markdown.html)
1. [Command line crash course](https://learnpythonthehardway.org/book/appendixa.html)
1. [Pro Git](https://git-scm.com/book/en/v2): Clone, commit, push, checkout branches, pull requests

### Visualization
1. [Mistakes, we've drawn a few: Learning from our errors in data visualization (The Economist)](https://medium.economist.com/mistakes-weve-drawn-a-few-8cdd8a42d368)
1. [The laws of shitty dashboards](http://attackwithnumbers.com/the-laws-of-shitty-dashboard)
1. Stephen Few's "Show Me the Numbers: Designing Tables & Graphs to Enlighten" is available in [hard copy (2012)](http://id.lib.harvard.edu/alma/990147829160203941/catalog) and an older version is available as workshop slides [here](https://courses.washington.edu/info424/2007/readings/Show_Me_the_Numbers_v2.pdf) (they are decently annotated and standalone)
1. [CRAP Talks #12 – Annabel St John-Lyle: Design Principles for Dashboards](https://www.youtube.com/watch?v=whFb00Z5bQo&feature=youtu.be): ~30 minute video
1. [Fundamentals of Data Visualization (Claus Wilke)](https://serialmentor.com/dataviz/)
1. [Avoid bar plots for continuous data! Do this instead: (Paul van der Laken)](https://paulvanderlaken.com/2018/12/17/avoid-bar-plots-for-continuous-data-do-this-instead/)
1. [TidyTuesday](https://github.com/rfordatascience/tidytuesday): Weekly social data project in R organized by the R4DS online learning community. Each week, they post a raw dataset for people to explore and share via the [#tidytuesday Twitter hashtag.](https://twitter.com/hashtag/tidytuesday?f=tweets&vertical=news&lang=en)
1. [Uncertainty + Visualization, Explained](https://medium.com/multiple-views-visualization-research-explained/uncertainty-visualization-explained-67e7a73f031b)

### R
Generally, having a well-defined project is the best way to learn. You'll end up searching for and finding more specific tutorials for the task at hand, but here are some places to get started:

#### Starting out
1. [20-minute end-to-end data analysis by Hadley Wickham](https://www.youtube.com/watch?v=go5Au01Jrvs): Crash course/example workflow; code/data linked in video description
2. [UBC's STAT545 curriculum](https://github.com/STAT545-UBC/Classroom)
3. [Practical R for Mass Communication and Journalism](http://www.machlis.com/R4Journalists/): Chapters 1-2 will get you through installation/setup 
4. [Wrangling data in the Tidyverse - Part 1](https://www.youtube.com/watch?v=E-Vvg8uzcVM&list=PL4IzsxWztPdnyAKQQLxA4ucpaCLdsKvZw&index=12&t=0s) (1 hr 15 min)
5. [How to Use R with Excel](https://rpubs.com/acolumbus/how-to-use-r-with-excel)
6. [Intro to R for Microsoft Excel Users](https://districtdatalabs.silvrback.com/intro-to-r-for-microsoft-excel-users)
7. [Regular Expressions in R – Part 1: Introduction and base R functions](https://paulvanderlaken.com/2017/10/03/regular-expressions-in-r-part-1-introduction-and-base-r-functions/)
8. [RMarkdown](https://rmarkdown.rstudio.com/lesson-1.html)
9. [Utah R Users Group YouTube channel](https://www.youtube.com/channel/UCcKPp7AI7ZTBf60WqXo3Bpg/videos), starting with:
    + [Exploratory data analysis with the tidyverse](https://www.youtube.com/watch?v=yYncj2FUO20) (40 min)
    + [Intro to data visualization with R](https://www.youtube.com/watch?v=BsoHElr7HpA) (1 hour)
    + [Branding and Automating Your Work with R Markdown](https://www.youtube.com/watch?v=pTpUp86-nwo) (47 min)
    + [Debugging and Profiling](https://www.youtube.com/watch?v=jSERTNhdeMs) (1 hour)

#### Fancier stuff
1. [The lazy and easily distracted report writer: Using rmarkdown and parameterised reports - Mike K Smith](https://resources.rstudio.com/rstudio-conf-2019/the-lazy-and-easily-distracted-report-writer-using-rmarkdown-and-parameterised-reports) (15 min)
1. [Happy Git and GitHub for the useR](https://happygitwithr.com/)
1. [Building an A/B Testing Analytics System with R and Shiny (Emily Robinson , rstudio::conf 2019)](https://resources.rstudio.com/rstudio-conf-2019/building-an-ab-testing-analytics-system-with-r-and-shiny)
1. [Data Science in a Box](https://datasciencebox.org): All lecture slides in "Exploring data" section
1. [R for Marketing Research and Analytics. Chapman & Feit 2015](./resources/r-marketing-research-analytics.pdf): Book with exercises
1. [rstudio-conf 2019 Workshop materials](https://github.com/rstudio/rstudio-conf/blob/master/2019/workshops.md)
1. [plotly: D3.js wrapper to make interactives from ggplot graphics](https://plot.ly/ggplot2/getting-started/)


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
  sections: "h2",
  subSections: "h3",
  insertLocation: 'append'
  });
</script>