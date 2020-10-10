---
typora-root-url: /home/lyc/Documents/LocalDev/physics-website/static/
---

# Applications of Feynman Diagrams

## Significance of Feynman Diagrams

With its simplicity and elegance, the Feynman Diagram has been applied liberally in particle physics explanations. Using just a bunch of lines and squiggly lines, Feynman was able to explain and solve problems involving subatomic particle interactions easily. His diagrams are brilliant illustrations that allowed us to predict other particle interactions after constructing a single example.

But it hasn't always been this way. When the first Feynman diagram was published, few physicists believed that it was a rigorous answer to the perplexing inconsistencies when dealing with "[Self-Energy](https://www.wikiwand.com/en/Self-energy)". Yet while Schwinger and Tomonaga's mathematical explanations were impressive, they were too complex to be applied effectively when we need to analyse more complicated interactions between more particles.

**The first Feynmann Diagram published in 1949**

![The first Feynmann Diagram published in 1949](https://physics.aps.org/assets/be0eeb33-4bba-4208-9bf9-2587acdf9c7c/e3_1.gif)

Fortunately, Dyson showed later in a classic paper that the 3 brilliant scientists' methods were equivalent. And for their work, they received the joint [Nobel Prize in Physics for 1965](https://www.nobelprize.org/prizes/physics/1965/summary/).

## Common applications

### Radioactive Decay

#### $\beta^-$ decay

In $\beta^-$ decay, we have a neutron spontaneously converting into a proton, an electron and an anti-neutrino. This can also be written as:

$$
n \to p^+ + e^- + \overline{v}
$$
This can be represented using a Feynman diagram too! Let's take a look (note that the vertical axis is space, while the horizontal is time):

![beta-minus-decay](/images/beta-minus-decay.png)

Wait, but what's $d$, $u$, $W^-$ and so on? Let's summarise it in the following table:

| Symbol | Name       | Description                    |
| ------ | ---------- | ------------------------------ |
| $d$    | Down quark | Makes up matter                |
| $u$    | Up quark   | Makes up matter                |
| $W^-$  | W boson    | Particle mediating weak forces |

It may seem a bit strange, but recall that a neutron consists of 1 up quark and 2 down quarks, while a proton consists of 2 up quarks and 1 down quark. Thus, by converting a down quark to an up quark, a neutron can become a proton!

With that out of the way, let's look at the diagram more closely. The top two solid lines represent the conversion of a down quark to an up quark, that's easy. Since we have a change in the flavour of quarks, we know that the weak force is involved here. Thus, we must have a $W$ boson acting as the middle-man. By applying conservation of charge on the top vertex, we can determine that it must have a charge of $-1$.

Now, the second vertex is where things start to get more interesting. When we learned $\beta^-$ decay, many of us probably wondered why an anti-neutrino is produced. It seemed very arbitrary, but here we see a rather nice explanation. According to the rules of Feynman diagrams, we must have **a real particle entering and exiting** each vertex. So far, we only have a real particle exiting ($e^-$), because the $W^-$ boson is virtual and doesn't count. Thus, there must be another particle that is entering! We draw another line, but this time, we have to direct it *backwards in time* to satisfy that condition, which tells us that this particle is an antiparticle. That's how we predict the existence of the anti-neutrino, and scientists have confirmed that through experiments.

## Fundamental applications

### Exchange forces, again

As mentioned in the previous sections, forces that we usually think of being due to a certain field can be explained using particle physics too! Here's a quick recap:

| Fundamental Force | Mediator      |
| ----------------- | ------------- |
| Weak Force        | W and Z boson |
| Strong Force      | Gluon         |
| Electromagnetic   | Photon        |
| Gravity           | Graviton*     |

*not confirmed yet, but this is the current scientific consensus

Do you remember what the forces we usually experience fall under?

{{< expand "See answer">}}

Electromagnetic forces! Normal force and friction are macro-level observations of repulsions between the charged particles of different atoms when you try to squish them close together.

{{< /expand >}}

To illustrate how these particles mediate these forces, let's look at a few examples (in fact, the nuclear decay explanation above is an instance of weak force in action).

### A pair of electrons, EM Force and Weak Force

What happens when two electrons collide into one another?

Well, they'll repel each other and fly apart, because like charges repel right? Usually, that is indeed what happens when we have a virtual photon mediating the EM force between the two, which we see in the following Feynman diagram:

![electro-mag](/images/electro-mag.png)



However, there is also another possible cause of this repulsion, albeit less common. That is, the $Z​$ boson could have been a mediator for a weak interaction between the electrons. Note that the $Z​$ boson and not the $W​$ boson is involved, because we have a neutral intermediate due to the conservation laws of particle interactions.

![electro-weak](/images/electro-weak.png)

## “Worked examples” of interactions with explanations

## [optional] DIY Exercises with answers for self-check

## References

* https://physics.aps.org/story/v24/st3

* http://hyperphysics.phy-astr.gsu.edu/hbase/Particles/feyn.html