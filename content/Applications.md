---
typora-root-url: /home/lyc/Documents/LocalDev/physics-website/static/
katex: true
weight: 6
---



![electrons repelling each other, with 2 photons](/images/repulsion-of-electrons.png)

Here, we are able to represent the ‘repulsion’ between two charged particles, or the electromagnetic force! In this diagram, one electron exchanges a photon with another, causing them to be shoved off in opposite directions. This is also known as Moller scattering. 

Here, we learn how they can be applied by examining the (known) Feynman diagrams for the fundamental forces of nature.

## Explaining the Electromagnetic Force

Interactions involving these fermions and bosons can be graphically described using Feynman diagrams. Let’s start by looking at an interaction between an electron and a photon. 

## Explaining the Strong and Weak Forces

We have thus far seen electromagnetic interactions. But how does it compare to the strong and weak forces?

![electrons repelling each other, with 2 photons](/images/comparison-of-forces.png)

These are the primitive vertices for the strong, electromagnetic and weak forces. How about gravity? Well, there are no diagrams for gravity because gravitons haven’t been observed (yet). 

Now that we've looked at some of the conservation laws, let's look at Feynman diagrams for the weak and strong force!

![electrons repelling each other, with 2 photons](/images/weak-force-diagram.png)

The weak force is perhaps trickier than the electromagnetic force. Usually, the chain of reasoning is a bit more complicated. Here, a neutron decays into a proton. We can see that the neutron and proton have common quarks, and the only difference between them is that the neutron has a 2nd down quark while the proton has a 2nd up quark. In this diagram, the down quark of the neutron first changes flavor to become the up quark of the proton. As the flavor of the quarks is changed, the weak force is at play here, and the boson emitted must either be the W boson or the Z boson. The charge of the down quark is $-\frac{1}{3}$ while the charge of the up quark is $+\frac{2}{3}$, so to conserve charge, it must be the W- boson. 

In the diagram, the interaction doesn't stop here, and the W- boson disappears eventually. For this to happen, the W- boson then emits an electron to conserve charge. However, as the electron is a lepton leaving the vertex, another lepton must enter the vertex by going back in time. Since this is not physically possible, we instead use the mathematically equivalent explanation that an anti-lepton must leave the vertex, and therefore the anti-neutrino must also be emitted. This interaction is also known as beta minus decay.

What about the strong nuclear force? The strong force is mediated by gluons. They are responsible for the attractive and repulsive forces between quarks.

![electrons repelling each other, with 2 photons](/images/protons-neutrons-gluons.png)

In this diagram, the whitish curly lines represent the gluons. You could say that gluons 'glue' quarks together!

![electrons repelling each other, with 2 photons](/images/nuclear-strong-force.png)

This is a diagram representing the strong nuclear force, or the repulsion between a neutron and a proton. Don't worry if it looks complicated! Some extra knowledge is required to understand this Feynman diagram, which is beyond the scope of this website. Nevertheless, we hope to give you a taste of what the strong force looks like in Feynman diagrams. To understand this Feynman diagram, you have to realize that quarks, in addition to their flavors (up, down, charm, strange, top, bottom), have color charges (red, green, blue). Anti-quarks also have their own anti-color charges (anti-red, anti-green, anti-blue). Gluons each come with a color charge and an anti-color charge (and hence there are 9 possible color combinations of gluons). Gluons are constantly exchanged between quarks, and you can see their color interactions in this diagram. With all these interactions, the net effect is that the proton and neutron are repelled from each other.

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



However, there is also another possible cause of this repulsion, albeit less common. That is, the $Z$ boson could have been a mediator for a weak interaction between the electrons. Note that the $Z$ boson and not the $W$ boson is involved, because we have a neutral intermediate due to the conservation laws of particle interactions.

![electro-weak](/images/electro-weak.png)

## “Worked examples” of interactions with explanations

## [optional] DIY Exercises with answers for self-check

## References

* https://physics.aps.org/story/v24/st3

* http://hyperphysics.phy-astr.gsu.edu/hbase/Particles/feyn.html
