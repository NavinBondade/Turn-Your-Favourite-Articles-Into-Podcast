# Transform Your Favourite Article Into Podcast
<p align="center">
<img src="https://media.wired.com/photos/6435f92f13021b2cf16d62ab/16:9/w_2400,h_1350,c_limit/AI-Podcast-GettyImages-1131242410.jpg">
</p>
<p>Reading is not everyone's hobby. It is not something everyone likes to do, but to gain knowledge through articles and books, we often sit and read. Reading also requires a quiet and relaxed environment, which is not always possible. This project helps to overcome all these limitations. Here, I have built an AI system that transforms your favorite article into an exciting podcast with a human-like voice. You can listen to this podcast anytime and anywhere, and if you are in a hurry, you can also increase the playback speed to save time.
</p>
<h2>Libraries Used</h2>
<ul>
  <li>Bark</li>
  <li>Scipy</li>
  <li>NLTK</li>
  <li>Numpy</li>
  <li>Trafilatura</li>
  <li>Streamlit</li>
</ul>
<h2>Methodology</h2>
<p>The AI system is divided into two sections: the first is web scrapping, and the other is transforming the web data into a podcast. Web scraping, i.e., extracting the article from the web, is done using the Trafilatura library. Once all data is gathered and filtered, it is broken down into individual sentences. This process is essential to overcome the context window problem of the mode. The model processes the individual sentences and transforms them into an entire podcast. The user also has the choice to select whether he wants to listen to the podcast in a male or female voice.</p>
<h2>BARK</h2>
<p align="center">
<img src="https://the-decoder.com/wp-content/uploads/2023/04/dog_headphones_bark_audio_ai_midjourney.png">
</p>
<p>Bark is a transformer-based text-to-audio model created by Suno. Bark can generate highly realistic, multilingual speech as well as other audio - including music, background noise and simple sound effects. The model can also produce nonverbal communications like laughing, sighing and crying.</p>
<h2>Demo Video</h2>


https://github.com/NavinBondade/Turn-Your-Favourite-Articles-Into-Podcast/assets/43030152/4bcbb69d-66b0-4aef-859c-6c085c81a4a9


<h2>Conclusion</h2>
<p>In this project, I created an AI system that transforms any article into a podcast, having a realistic human voice and engaging narration. The user only has to provide the article's URL, and the system will generate a podcast version of the article using the Bark model. Users also have the option to choose different male and female voices. </p>
