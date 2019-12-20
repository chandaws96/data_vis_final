## Introduction

The 2016 presidential election is one of the most contentious elections in American history. A political outsider, despite losing the popular vote, manage to overcome his establishment counterpart. This victory brought success across the board for the GOP party, with a large majority in both the House and the Senate. It also allowed them the ability to secure two supreme court nominations. With this success, Trump has now become the symbol of the party, meaning that the public's perception of him directly reflects the public's perception of the Republican party.

The midterms of 2018 reveal this fact clearer than ever, with a sharp swing to the democrats in the house of representatives. In figure I below, the vote counts for every congressional district are shown, as well as which party won the district and if the district's representative endorsed trump in 2016. The first year 2014 is shown to give a comparison to how different the 2018 midterm elections were in comparison to years past. If play it hit on the graphic, or the year scroll bar is used, a depression can clearly be seen in the change between 2016 to 2018 of the republicans that endorsed trump. While not highlighted specifically, most of the maroon dots that are now cleary among democratic districts represent the several endorsers who lost their seat in the election. 


##### Figure I


<iframe width="750" height="500" frameborder="0" scrolling="no" src="//plot.ly/~cad162/1.embed"></iframe>

These results bring up an interesting question, given how tied the GOP party is to the current president, of how much of Trump's discourse is affecting the party. In traditional election years, the president will go out and help campaign in the midterm elections to help support his/her party, and Trump is no different. The difference comes in his unfiltered approach to political speeches, seemingly unafraid of saying anything on his mind or attacking anyone he pleases. In this analyses, the different speech topics and words chosen will be analyzed both before and after the midterm election to see the topic's Trump most used in the midterms and if he has changed after the midterm loss.

## Methodology

In order to analyze the discourse in an non subjective way, a machine learning approach called topic modeling will be used. Topic modeling is a sub-branch of machine learning called natural langauge processing, which attempts to use textual information as data in computer models rather than numbers. The topic model that will be used is called Latent Dirichlet allocation (LDA), which is an unsupervised learning technique, where the only real parameter about the results is the number of topics the model will find. In this model, after specifying the number of topics and the text to use, the computer will analyze the frequency of terms that are used in the text and output topics based off the uniqueness of the combination of terms. The output, in the case of Trump's discourse, will be a list of topics that are most frequently used, along with the weights of which words were most important to each topic. After seeing the words used, and their weights, it will be fairly easy to infer what subject matter is present in each topic computed, allowing inferal into the the strategies used by the president leading up to and after the midterm election.

The analyses will use 10 speeches that happened in the month prior to the election and 10 speeches in the month after the election as two different corpuses of text. 


<img src="Graphs/LDAafter.png" alt="hi" class="inline"/>
