Lorenzo Mario Amorosa

Sami Mohammed Osman

Introduction to the Divine Comedy

The Divine Comedy is an Italian masterpiece written by Dante in the XIV century. It is made of hendecasyllabic verses, all grouped in terzina, and it has a fixed rhyme scheme. Several previously written masterpieces, such as the Iliad and the Odyssey, have a strict and well known metric scheme as well.

This stylistic choice can be understood by thinking about that fixed and well thought out metrics facilitate the handing down of the work. In antiquity works were recited orally and hence a fixed rhyme scheme could help actors to remember phonetically words during the acting itself.

In addition to both rhymes and well thought out metric structure, images have a fundamental role in the Divine Comedy, in particular through figures of speech, such as metaphors and allegories [1]. As an example, we now take a look at I canto of Inferno:

● Dante initially gets lost into selva oscura, metaphor of sin

● then he meets 3 beasts:

○ the loin allegory of sensuality

○ the lion allegory of pride

○ the wolf allegory of greed

● then he meets Virgilio, allegory of human reasonableness, who proposes himself as Dante's travel guide

Each one of 100 canti of the Divine Comedy is plenty of information which hints to images, in particular it is plenty of lexemes, which are atomic concepts, which meticulously describe reality and which are semantically highly detailed.

It has to be recognized that metaphors and allegories have a fundamental and central role in the masterpiece, indeed they bind indissolubly together images and words. The information is surely denser in words or in a terzina, but it is explicitly clearer in the associated image.

It must be mentioned that Dante's topics are often really controversial, e.g. the sin, human protagonism, politics, Virgilio, and metaphors and allegories are widely used to describe them.

Deep Comedy - ideally

A good principle that could lead to the implementation of a neural network capable of generating a canto of the Divine Comedy must take into account the previously described facts. The neural network should ideally learn to associate words in a given terzina and its rhymes to the relative images.

At the state of the art it is scarcely feasible, but now we will illustrate our attempts to face the problem.

Deep Comedy - for real

We initially started to experiment with really simple models, such as plain RNN, LSTM and GRU, which in other scenarios led to impressively good results[2], but the performances were not acceptable. As a consequence, we decided to implement more complex models, such as Transformers[3], which performed really well.

The zip file we provide contains the code needed for the implementation of the Transformer capable of generating a canto, and it is organized as follows:
