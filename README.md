A. Let’s start with the basics

1. Can you implement the sing() method for the bird?
2. Now, we have 2 special kinds of birds: the Duck and the Chicken... Can you
implement them to make their own special sound?
3. Now how would you model a rooster?
4. Can you model a parrot? We are specifically interested in three parrots, one that
lived in a house with dogs one in a house with cats, the other lived on a farm next to
the rooster.

B. Model fish as well as other swimming animals
1. In addition to the birds, can you model a fish?
2. Can you specialize the fish as a Shark and as a Clownfish?
3. Dolphins are not exactly fish, yet, they are good swimmers

D. Model animals that change their behaviour over time
1. Can you model a butterfly?
2. Can you optimize your model to account for the metamorphosis from caterpillar to
butterfly?

E. Counting animals
Suppose you have an array of animals, e.g.
Animal[] animals = new Animal[]{
new Bird(),
new Duck(),
new Chicken(),
new Rooster(),
new Parrot(),
new Fish(),
new Shark(),
new Clownfish(),
new Dolhpin(),
new Frog(),
new Dog(),
new Butterfly(),
new Cat()
};
Note: The above instantiation may be different if you chose to set up your object model
differently… (hopefully you did)
1. Can you share the code to count:
a. how many of these animals can fly?
b. how many of these animals can walk?
c. how many of these animals can sing?
d. how many of these animals can swim?

BONUS
If you still have time left, please consider the following:
1. Can you add a second language (if you know a language other than English) Use the
rooster as a PoC for demonstrating this. For example, this is how the Rooster sounds
differently depending on language. Please add the rooster sound in your native
tongue.
• Danish: kykyliky
• Dutch: kukeleku
• Finnish: kukko kiekuu
• French: cocorico
• German: kikeriki
• Greek: kikiriki
• Hebrew: coo-koo-ri-koo
• Hungarian: kukuriku
• Italian: chicchirichi
• Japanese: ko-ke-kok-ko-o
• Portuguese: cucurucu
• Russian: kukareku
• Swedish: kuckeliku
• Turkish: kuk-kurri-kuuu
• Urdu: kuklooku
2. Can you design a RESTful API for querying these animals?
