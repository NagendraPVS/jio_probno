<h1 style="text-transform:'uppercase'">JIO PROBNO</h1>
<h2>Documentation</h2>
<h2>task5-few-shot bioacoustic event detection</h2>
<u><h3>Intro</h3></u>
<p>The term bio implies <q>living things<q> and acoustic implies <q>property of sound</q> , as a whole the aim is to detect events of living things such as barking etc,are need to be detected using the unique acoustic properties of each specie. </p>
  <p>Further,the term few shot means a type of learning (like supervised learning) in which few shots or audio recording of each class are taken and model is made for prediction of that specific class or specie.<p>
  <p>It is studied using N-way-k classifiction where N means number of species and k means the no of shots of each specie needed to make model</p>
  <p>few shot learning strategy is far different from supervisied learning, in the following ways </p>
  <ul>
    <li>few shot learning needs lesser datset or samples compared to supervised learning</li>
    <li>few shot learning makes generalisation from the combination of trained data samples</li>
    <li>few shot learning classifies new examples with less or small data set support</li>
    
  </ul>
  
  <br><br>
  <u><h3>Architecture</h3></u>
  <p>In the few shot classification ,while prediction we give an audio sample and some events that we want to identify such as barking etc to an algorithm(we prefer) that can detect event based on sound(sed) .The output will be the offset and onset of the event occured in the audio sample given which was clearly shown in the below figure</p>
  <p>The below figure clearly the describes the aim, input and output of the project</p>
  <img src="https://dcase.community/images/tasks/challenge2021/few_shot_bioacoustics.png"></img>
  <br><br>
 
   <u><h3>Analysic from papers</h3></u>
   <p>Challenging thing in this task is few shots ie having few labelled sets. Prototypical networking strategy is said to have good prediction for the lower dataset samples due to limited training data </p>
   <p>The other main challenge is difficult to identify the desired event in the given audio sample due to various unlabelled samples present in input audio</p>
   <p>Most of the papers described that the test set should be categorised into positive embedding , negative embedding and query set for better generalisation or predictions</p>
   <p>Few shot image classification (FSIC) approach is said to better suits the few shot bioacoustic event detection which roughly categorized the methods int
  <ul>
    <li>semi-supervised</li>
    <li>transductive based</li>
    <li>inductive based</li>
</ul>
</p>
