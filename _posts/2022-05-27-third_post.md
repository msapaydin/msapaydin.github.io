# Game AI vs. Industrial AI vs. academic AI 

I have been teaching artificial intelligence related classes since 2015. I have also consulted industry for AI. Recently, I have also started teaching AI in digital games.
What I can say that, even though the basics are the same, the AI for these three areas are quite different.

* For Game AI, the metric to optimize is the player's experience while playing the game. So for instance for planning the path of a non playable character (NPC), unlike robots following a target in evader algorithms, the position of the player from the game scene graph can be made available to the NPC.

* For academic AI, the metric to optimize is the number of (hopefully of high quality) papers. So one is rather interested in publishability, and state of the art contributions especially for top conferences and journals. This can be a new optimization algorithm that optimizes the loss function of a neural network faster than stochastic gradient descent for instance. Or, a way to decide on the number of hyperparameters or layers of a neural network automatically.

* For industrial AI, the metrics to optimize are business metrics and practicality of the approach. Something that can be implemented, trained and deployed easily is preferred over a method that is the state of the art in terms of theorerical guarantees. The business metrics may not be aligned with the metrics used in optimizing a machine learning algorithm.

Most students in academia are focused on industrial AI. Most profs in academia are focused on academic AI. As a consequence, the students are usually exposed to academic AI content in their AI classes. Furthermore, even though some classes do exist which target industrial AI (such as EE543 that I have taught this semester at Izmir Institute of Technology based on fast.ai materials), these materials are also not exactly what you would expect in an industrial environment, where the business metrics are entering into the equations.

Industry should be careful in choosing who to work with for their business needs. A top prof in the number of publications on AI may not be the best person for an industrial application.
