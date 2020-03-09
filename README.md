# OrderAndChaos
My course planning for my Order and Chaos course at Srishti Institute of Art, Design, and Technology
# Course Modules for Math Models in Art and Design - Order and Chaos
### October 2019
@(Course Plans)[Marxico]

[TOC]

The course is based on large Human Experiences that can form the basis for **Model-based** Thinking.  

Each of the following Section Titles is an *Abstract Noun* that represents on such **Human Experience**. The understanding of each Human Experience is intended to lead to a Model, in the manner of Charlie Munger and Scott E. Page.  The Human Experience + Model will be, in each case, motivated by contemplating a well known Story, or a Drama, and a Painting. The Models may resemble a Thought Experiment, or a Diagram, or a simple Procedure or Math Formula, or a piece of Computer Code. The Models are intended to provide directions for artistic and design endeavours.

The Models will be understood, internalized, fitted in with what we already know, and generalized to new applications. This will done with the help of activities based on games, videos, art-related activities, open source software tools, field experiments, field visits, additional readings, writings and discussions. 

## Symmetry
- Elizabeth Barrett Browning “Sonnets from the Portuguese” and William Blake “Tiger,Tiger"
- Activity: [Internet Anagram Server](wordsmith.org)
- 1D and 2D Symmetry; Dimensions
- Motivate “Canonical Movements” and Operations (Translation / Rotation / Reflection / Glide Reflection)
- Friezes / Lattices / Wallpapers / Kolams / Sona Art / Fibonacci Kolams / Ethno-mathematics
- [Saty Raghavachary](https://www.youtube.com/watch?v=-l9za7UlzKM)
##### Orientation
- To be Written up properly (TBD) 
- Introduction to L- Systems; Interpretation of Kolam as L- System: Iterations
- Activity: Frozen Light: https://imaginary.org/program/frozenlight
	- links to Paulus Gerdes “Light + Mirrors” method of creating Sona patterns
	- Girih Art from Isfahan: <https://3dwarehouse.sketchup.com/search/?q=girih&searchTab=model>
- Questions: 
- Can this be linked to Peano’s “Monster Curves”? 
    * By creating smaller and smaller grids, ( repletion / scale..) can we create Koch snowflake like drawings from Sona art? (Gerdes, page 22 - 2)
* Use R to do some of this:
    * Deldir for [Mandalas](https://fronkonstin.com/2018/02/14/mandalas/)


##### Rhythm
- Music as synchronized and coordinated motion
	 - Nathan D. Hesselink: [Radiohead’s “Pyramid Song”: Ambiguity, Rhythm, and Participation](http://www.mtosmt.org/issues/mto.13.19.1/mto.13.19.1.hesselink.php) and [PDF](http://mtosmt.org/issues/mto.13.19.1/mto.13.19.1.hesselink.pdf) and PDF [Examples](http://mtosmt.org/issues/mto.13.19.1/hesselink_examples.pdf)


## Proximity 
   - Problems with Kandinsky Math Artist: Examine his artistic credo and motivate
   - Motivate the idea of “Proximities” and Metrics to measure Proximity
   - Emotional and Psychological effect of Proximity
   - Motivation for Voronoi Diagrams
   - John Snow and the epidemic in Soho
	   - Analysis using Voronoi diagrams in R ( R Package: deldir)
   - Florence Nightingale and her Coxcomb chart and how she could have used a Voronoi diagram
   - **"Painting with Distance"**
	   - GPS Art Exercises with Strava
	   - Exercises with Google Literature Trips and Google Earth
	   - Voronoi Self-Portrait using GeoGebra or R + deldir following [Fronkenstin](https://fronkonstin.com/2017/03/07/frankenstein/)
	   -  Activity: Kolams on a Map: City centres as pulli-s
	   -  Activity: Kolam based story illustration


## Connectivity
- 	Set up [Barabasi's cocktail party](http://networksciencebook.com/chapter/3) experiment in class, with chocolate instead of wine. 
	- 	Coin tossing to set up meetings; ( 2 heads to talk => p=0.25 etc.); 3 minutes per meeting
	- 	Also have one handy juicy rumour to spread. 
	- How long does it take for each person to have had chocolate? Average of one meeting...
	- Discussion on how this is an Erdo Renyi model, since pure randomness was the basis for any encounter being fruitful
- 	Vimeo Video [Six Degrees of Separation](https://vimeo.com/14196818)
- 	Introduction to Networks and Graphs [Dmitry Zinoviev](https://www.slideshare.net/DmitryZinoviev/workshop-20212296)
- 	Live coding in R with the [tidygraph package](https://www.data-imaginist.com/2017/introducing-tidygraph/)
		- 	Structure ( Node/ Link / Directed / Undirected /....)
		- 	Dynamic Processes: 
				- Random Networks - Erdos-Renyi model
				- Small World: Watts - Strogatz model
				- Hubs and Power Laws - Barabasi - Albert model
				- Preferential Attachment ( Rich get Richer ) - TBD
- 	Readings from : Networks, Market and Crowds - [Easely and Kleinberg](http://www.cs.cornell.edu/home/kleinber/networks-book/)
- Activity: 
	- Check out the Kevin Bacon number of your favourite actor
	- Find a Keven Bacon in Srishti Foundation
	    - Collect Data from across college, import and plot, analyze and comment on Centrality Measures
	    - Use this online tool at databasic.io [Connect the Dots] (https://www.databasic.io/en/connectthedots/) or better still at [GraphCommons](https://graphcommons.com/graphs/new)
 - Import any of the Sample Network Data Sets that make sense
	- Take your favourite Literary Work / TV Serial / Movie and create a Network Database for it. Visualize it either with or without tech tools  From Teach Engineering, this [Activity](https://www.teachengineering.org/activities/view/uno_graphtheory_lesson01_activity2)
	
	
- Network Science Ideas: 
	- Use [NetLogo](https://ccl.northwestern.edu/netlogo/download.shtml) to Examine and Understand some Network Science Models : 
		- Friendship Paradox, Kevin Bacon Number
		-  Random Networks, Clustering, Small Worlds, Preferential Attachment, Scale-Free networks
			-  Mathew Effect from Bible
		-  Euler Walk, Bridges of Konigsberg
		-  Hamiltonian Walk and Journeyman Problem
		-  [Bidding Market Game in NetLogo]( http://ccl.northwestern.edu/netlogo/models/BiddingMarket) as a view to **Stock Market** workings
	- Real World Examples
		- CityLab Blog: [How Cars Divide America](https://www.citylab.com/transportation/2018/07/how-cars-divide-america/565148/?utm_source=feed)
		- Disease Propagation [Game](vax.herokuapp.com)
		- Disease Propagation and Epidemics and Percolation Theory : Kevin Smiler - Going Critical - [Models for Disease Diffusion](https://meltingasphalt.com/interactive/going-critical/)
		- ""How to Win Friends and Influence People": [Diffusion Simulation Game](https://www.indiana.edu/~simed/istdemo/) and [PDF](http://www.enablingchange.com.au/Summary_Diffusion_Theory.pdf)
		- Read one Stock Market Crash / Bubble Story [TBD](Where is my story!!)
		- Read and Analyze Frigyes Karinthy's Short Story *Chains*
		- Cambridge Analytics story? [TBD](Cambridge Analytics)
- Activities: 
	- Try to replicate Steve Millgram's experiment to motivate Small World
	- We are Fine
	- Analyze BMTC routes in R using DiagrammeR : [ Data Source ](https://github.com/geohacker/bmtc)
	-  Tristan Mahr - [Secret Santa is a graph traversal problem](https://www.tjmahr.com/secret-santa-graph-traversal/)
	- Use Arduino / Makey Makey + Phone BT to create a "connected set of streets" in class
	- Network Theory in Art : Make Paper/ Rangoli / Thread Kolams and Sona Art using a printout of a Map as a background
	- Use and analyse/depict one dataset from the Stanford Large Network Dataset Collection [SNAP](https://snap.stanford.edu/data/index.html)
	- Use this online tool at [Network Repository]~~(http://networkrepository.com/graphvis.php)~~ Too Complex for now. 
	
- References
	- Albert-Laszlo Barabasi's book ["Linked"](http://networksciencebook.com)
	- David Easley, ["Networks, Crowds and Markets"](http://www.cs.cornell.edu/home/kleinber/networks-book/)
	- Robert A. Hanneman and Mark Riddle - ["Introduction to social network methods"](https://faculty.ucr.edu/~hanneman/nettext/)
	- Hiroki Sayama, ["Introduction to the Modeling and Analysis of Complex Systems"](http://bingweb.binghamton.edu/~sayama/textbook/)
	- Dmitry Zinoviev's [Little Network Science Lab](http://networksciencelab.com/)
	- Networked Life by Michael Kearns: [Online Video Version](https://www.cis.upenn.edu/~mkearns/NetworkedLifeOnline/)
	- Mark Newman: Networks
	- Marcia Ascher: Ethnomathematics
	- Paulus Gerdes: Lunda Geometry
- Visualization
	- Ognyanova, K. (2019) [Network visualization with R](www.kateto.net/network-visualization) and Tutorial [PDF](http://www.kateto.net/wp-content/uploads/2019/06/Sunbelt%202019%20R%20Network%20Visualization%20Workshop.pdf)
	- Network Repository http://networkrepository.com/graphvis.php
	- [Fun Stuff with Network Science](https://sites.google.com/a/binghamton.edu/netscied/fun-stuff)
	- [60 Graph Visualization Libraries](https://www.kdnuggets.com/2019/05/60-useful-graph-visualization-libraries.html)
	- Meeks, E., & Krishnan, M. (2013). [An interactive introduction to network analysis and representation](http://dhs.stanford.edu/dh/networks/)
	- Database for Social Networks in Movies http://www.moviegalaxies.com

## Repetition / Recurrence / Iteration / Periodicity / Coherence / Aggregation / Unison / Imitation
- Mitchell Resnick: [Beyond the Centralized Mindset](https://llk.media.mit.edu/papers/decentralized/)
- Motivate "individual, simple rules" that lead to "emergence of patterns" as a central idea
- Motivate Philip Anderson's idea "More is Different" [PDF](https://www.tkm.kit.edu/downloads/TKM1_2011_more_is_different_PWA.pdf)
- Simple and not so simple Phenomena
	-  Mexican Wave and Clapping Patterns
	-  Arpita Baypeyi’s Idea: "Repetitive Patterns in Dance - Kathak"
	-  Kannada Proverb "Gumpinalli Govinda"
	-  Douglas Hofstadter, "Ant Fugue" in his 1979 book 
	-  Use the "Rain" video (though that does have Central Control...)

##### Emergence and Complexity

- Understand bBasics of Systems, Simulations and Feedback Loops 
	- Nicky Case's website [Loopy : a tool for thinking in systems](https://ncase.me/loopy/)
	- Modelling with STELLA Systems Modelling <https://www.iseesystems.com/welcome.aspx>
	- A Tale of two Dirks:
		- Dirk Brockman [Research in Complex Systems](http://rocs.hu-berlin.de/)
			- [Complexity Explorables](http://www.complexity-explorables.org)
	- NetLogo and ABM Model exploration
	- 

##### Growth Functions
- Growth / Repetition as a “natural” operation 
      - Extract from Dawkins ** The Selfish Gene **
      - Extract from D'Arcy Wentworth Thompson ** On Growth and Form **
      - NetLogo Examples
##### Fractals
   - Benoit Mandelbrot's [TED Talk on Roughness](https://www.ted.com/talks/benoit_mandelbrot_fractals_the_art_of_roughness?language=en)
   - Complex Algebra, 2D plane, 
   - Geometric interpretation of Canonical Operations
	   - Translation, Reflections, Glide Reflections, Rotations
   - Iterations
##### Chaos Theory
   - Chaos from Deterministic Iterations
   - Frame - Golubitsky: Symmetry on Average
   - Activity: Fractals : Julia and Mandelbrot using [XaOs](https://sourceforge.net/projects/xaos/) or equivalent
   - Examples: [Fractal Antennas](http://www.ece.iit.edu/~pfelber/fractalantennas.pdf) by Phil Felber
- References
   - ComplexityExplorer.org
   - [Yale Fractals Course](https://users.math.yale.edu/public_html/People/frame/Fractals/)
   - [Fractal text analysis of James Joyce's Ulysses](https://phys.org/news/2016-01-world-greatest-literature-reveals-multifractals.html)
   
#####Rationality, Human Behaviour and Game theory
   - Alexander Dumas “ The Three Musketeers” as a Manifestation of “Prisoner’s Dilemma”
   - South West Airlines episode
   - Public Behaviour and extract from V S Raghunathan’s “Games Indians Play"
   - Axelrod Experiment and Strategy
   - Play Prisoner’s Dilemma Game on Nicky Case Website [Trust Game](https://ncase.me/trust/)
   - Schelling Segregation Experiment (Nick Case website)
   - Hotelling’s experiment from [Presh Talwarkar’s Book](https://mindyourdecisions.com/blog/tag/hotellings-game/)
   - Schelling Points as an "Emergent Phenomenon" ( Preface of Thomas Schelling's Book, example on Audience Seating )
   - Visit to local “urban ghetto”
   - Blockchain or Email + Timer based stock exchange: 
	- random cheating, personal values and strategies, 4R ( Reward, Risk, Regret, Repetition)
   - Wishlist: Create Bitcoin economy in class using a captive Bitcoin installation

##### Fourier Series and Music Synthesis
- Wordsworth’s “Solitary Reaper” and “Tower of Babel”
* Motivate Music as common emotional language; PsychoAcoustics
* Gallopin' Gertie Bridge: <https://www.youtube.com/watch?v=j-zczJXSxnw>
	* Vibration and Resonance, Idea of Acoustic Length / Natural Frequency
	* Example of Childhood Swing: How did Dad/Mom know when to push your swing?
    * Activity: Measure vibration frequencies from common objects and tabulate "Acoustic Length" of objects
- Using Simple network Graphs to construct Musical Scales (https://imaginary.github.io/ScaleLab/ 
- Activities:
	- Arduino and Sound Projects TBD
	- Use Mozart’s Random Music generator and Online Music Sequencer
	- Use R packages "seewave", "soundgen", "phontools" and "tuneR" to synthesise sound algorithmically in R
###### Music Theory Stuff
- Introduction to Sound Synthesis and Systems Theory
	- Complex Rotating Vectors, Symmetry and Fourier series
	- Decomposition and synthesis: Music
	- Ear as FFT analyser
	- **Eigen Functions** and how they are like an alphabet
	- Musical instruments and Timbre
###### SuperCollider Stuff
- Activity: SuperCollider for Algorithmic [Sound Composition](https://en.wikibooks.org/wiki/Designing_Sound_in_SuperCollider); SuperCollider Code [Examples](http://ecmc.rochester.edu/ecmc/docs/supercollider/examples/)
- James Harkins [Patterns in SuperCollider](http://distractionandnonsense.com/sc/A_Practical_Guide_to_Patterns.pdf)

## Randomness
##### Probability, Frequentist and Bayes Estimation
-  Hamlet “To be or not to be”
    * Motivate uncertainty, randomness, information gathering and experiments
    * Plot of Traffic Data, Histograms
    * Means, Variances and Medians
    * Poisson Process
- Is Randomness good?
    * Randomness as “Fairness” : Sharing Mangoes during Childhood
    * Creating Randomness ; Randomness as a Tool
    * Experiment design: Blindness
    * MonteCarlo experiment to calculate pi
    * Generating Random Numbers as Modelling in Monte Carlo methods
##### Hypothesis Testing and Design of Experiments
- Observational and Interventional
- College Survey: 
	    - Set up Hypothesis
	    - Design Randomized Observational Sampling Experiment
	    - No of Readings/Samples to get good Confidence Intervals
	    - Standard Errors, CI
	    - Motivate [Allen Downey Stat Test](http://allendowney.blogspot.com/2016/06/there-is-still-only-one-test.html)
#####Bayesian Estimation
- Bayesian Estimation using [Harry Potter](https://link.springer.com/article/10.3758/s13423-017-1262-3)
- David Robinson: Understanding empirical Bayes estimation (using baseball statistics) <http://varianceexplained.org/r/empirical_bayes_baseball/>
- Rasmus Baath [Bayesian Estimation in R](https://docs.google.com/presentation/d/1Lv5_IBi_PXbtp8FbA8-qBI0PwJAvPlP9OZ-6t6l6gwM/edit#slide=id.p)
- tidybayes: Bayesian analysis + tidy data + geoms <https://mjskay.github.io/tidybayes/>
- [Become a Bayesian master with bayestestR](https://github.com/easystats/bayestestR)

## Estimation
##### Interpolation / Regression
- Use Greek Chorus and the Sutradhar concept as an introduction to Interpolation and Regression:
- [Legally Blonde: Greek Chorus in Popular Culture](https://www.youtube.com/watch?v=aVRUfPRUKtU)
- [The Greek Chorus Explained](https://youtu.be/orXPMdCU-6s)
- [Indian Drama and the Sutradhaar](https://www.britannica.com/art/theater-building/Developments-in-Asia#ref463835)
- Motivate the idea of "Missing Data" and Interpolation
- *Robert Grant's website* : generate random dataset by painting it: http://www.robertgrantstats.co.uk/drawmydata.html
	- Use random data for regression/interpolation in Excel or in R or [jamovi](https://www.jamovi.org/)
- Continue with Regression, Learning, Estimation
- Wisdom of Crowds, Averaging
- Stephen Stigler: Seven Pillars of Statistical Wisdom

## Adaptation
To be written up
- John Holland
- Adaptive Equalizers?

## Modularity
To be written up
link this to Symmetry


## References
- Symmetry
    * Doris Schattschneider
    * Brian Sanderson <http://www.math.toronto.edu/~drorbn/Gallery/Symmetry/Tilings/Sanderson/Algorithm.pdf>
    * Joe Rosen
    * Marcia Ascher “Ethnomathematics”
    * Paulus Gerdes
    * Darrah Chavey
    * Jay Kappraff
    * Kristopher Tapp’s website and PPTs; 
    * Rachel Wells
    * Warren Weaver
    * Prof. Naranan’s PPTs
- Fractals, Chaos and L-Systems
    * Frame and Golubitsky
  
- Game Theory
    * Presh Talwalkar,"The Joy of Game Theory"
    * Robert Axelrod," The Evolution of Cooperation"
    * Brian Skyrms," The Social Constract"
    * V.S Raghunathan: Games Indians Play
    * 
- Sound
    * Trevor Cox
    * Daniel J Levitin: The Story of the World in Six Songs
 
- Statistics
	- Stephen Stigler: Seven Pillars of Statistical Wisdom
	- David Spiegelhalter: The Art of Statistics
	- Derek Rowbotham
