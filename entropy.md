# Entropy

## Irreversibility

Entropy is a theoretical quantity that explains irreversibility in physics. Known laws of physics are reversible, which means some physical process would be equally valid both forwards or backwards in time. (For everyday phsyics, this statement is exactly true, whereas for some processes in high energy physics the time-reversed version of a process would also have to be mirror-image reversed as well in order to be valid, whereas for everyday physics, mirror image reversal is also an exact symmetry.) However, in ordinary experience, many unexceptional processes would be quite exceptional if they were reversed. No one, for example, has ever experienced a convergence of sound waves into a puddle of liquid and pieces of glass sufficient to project them into the air and together in his hand as an unbroken cup of hot tea but many people have experienced the time-reversed version of such a process.

Thus, we observe that physics is irreversible on an everday scale but in all controlled conditions designed to experiment with fundamental processes, physics is reversible. The resolution of this apparent paradox follows from a statistical understanding of the physics in our everday experience. Not knowing the precise interactions of all particles around us, we have no recourse but to treat the evolution of our everyday environment as random. The relevant features of our experience do not depend on the exact position of every particle in our environment. Rather, many possible configurations of matter would result in indistinguishable experiences. 

If our world is indeed random, then it follows that a state with more states that are similar to it is *more likely* than one with fewer. This conclusion explains irreversibility in everyday physics. An irreversible process in everyday experience is not literally irreversible, but is a transition from less likely state to a more likely state. Indeed, different configurations of matter might be indistinguishable from vastly different numbers of similar configurations, which means that some possibilities are so unlikely that they never happen. To put it concretely, among all states in which there is a puddle and broken teacup on the floor, there are vastly fewer similar states with perfectly prepared tea than without, whereas among all states with perfectly prepared tea there are relatively many similar states with a puddle and a broken cup. 

A configuration that is similar to fewer other states is considered to be low entropy and one that is similar to many others is high entropy. Evolution from low to high entropy is likely, whereas high to low is unlikely, though not impossible. That is all that entropy is and all that it implies. 

## Entropy as Disorder

Entropy is often characterized as an expression of the disorder of a system. I think that this analogy is difficult to make sense of and tends to provoke the imagination in unhelpful directions. Furthermore it provokes questions about the nature of order that are not needed to understand entropy. Entropy as irreversibility strikes the heart of the matter. 

## The Second Law of Thermodynamics

Entropy is strongly associated with the second law of thermodynamics, which states.  

2. **In a closed system, the entropy never decreases.**

This law follows from the concept of entropy described above. If entropy never decreases then only a processes with constant entropy could be reversible. It would not need to be independently stated except that entropy was introduced by Clausius not as a quantity related to the number of states a system could attain, but as an unknown quantity $S$ given in terms of energy $E$ and temperature $T$ that was used to explain the observed maximum efficiency of engines. 

$$ \Delta S = \frac{\Delta E}{T} $$

If entropy must always go up, then this expression explains why heat moves from hot places into cold. The $\Delta E$ is interpreted as negative when heat is leaving a system and positive when entering. If a quantity of heat energy moes from a hot system to a cold one, then the negative change in entropy in the hot system has a smaller absolute value than the positive change in entropy of the cold system, due to temperature being in the denominator. Thus, the total change in entropy is positive when heat energy moves from a hot system to a cold one and negative if it moves from cold to hot. 

## Entropy and Temperature 

The relation above can be rearranged into a definition of temperature. 

$$ \frac{1}{T} = \frac{d S}{d E} $$ 

This is how modern physicists think about temperature. Thus, temperature was a fundamental quantity when entropy was first proposed, but now entropy is seen as fundamental. 

This relation makes sense in terms of the concept of entropy given above because if the number of states in one system $B$ is going up more as more energy is provided to it than another system $A$, then one would expect it to be more probable for energy to flow from $A$ to $B$ than from $B$ to $A$. 

## Maxwell's Demon

Entropy can't go down because we can't stop rolling dice with the universe. Thus, more probable states are inevitable. In quantum physics, probability is conceived as a fundamental property of a physical state, whereas in classical physics it is not. However, a deterministic process that consists of many interacting parts may be indistinguishable from one that is probabilistic. Therefore entropy matters even when quantum mechanics does not. 

Yet when that is the case, where is the entropy? It appears to be something in our minds that exists because of our inability to comprehend the system in its true detail. How can entropy be so powerful if it is not even real? A thought experiment known as Maxwell's Demon has taught physicists that even beingns without the need to look at a complex interacting system as a statistical ensable cannot reverse entropy. 

Maxwell's Demon was introduced by Maxwell in an offhand way to demonstrate the opposite, ie, that entropy no longer exists without statistical physics. Maxwell proposed a system with two chambers filled with a gas and a small slit connecting them. An entity with the power to observe individual particles of gas would open or close the slit when a gas particle moved near it based on what it observed about the particle. The entity could allow cold particles to pass in one direction and hot particles in the other. In this way the demon could control the flow of heat to be entropically negative. 

Physicists after Maxwell have showen that the demon, in fact, *cannot* do this. 

## Entropy as Negative Information

Although information is sometimes said to be negative entropy, it is easier to understand entropy in terms of information and say that entropy is like negative information. 

Information Theory was developed by Claude Shannon in *A Mathematical Theory of Communication*. There, he showed that every message could be encoded as a sequence of bits. If the total number of possible messages that could be transmitted over a certain channel in a given amount of time is $M$, then the number of bits in one message is $log_2 (M)$. Shannon defined the information content of a message to be the number of *meaningful* bits in a message. In other words, depending on how messages are enecoded, there may be more than one possible message that all have the same meaning. The differences between these messages do not count toward their information content. If, of those $M$ messages, $N$ possible meanings can be encoded, then the information content of the channel is $log_2 (N)$. The entropy, then, is the number of redundant bits in the message, which is $log_2 (M - N)$. 

Entropy in a physical system works the same way, which makes sense because any physical system can be interpreted as some kind of message. The big difference is that physicists use $log$ base $e$ instead of $2$. The entropy of the system is a logarithm of the number of states that are indistinguishable, given the information we have about it. 

The concept of the *number of states* needs some clarification. Typically, a physical system will take up a certain volume $V$. This is analagous to thinking of messages in terms of what can be transmitted in a fixed amount of time. There is also a certain energy $E$ in that volume. This is analagous to a channel of communication having a certain maximum frequencey. Under these conditions, the number of states in a quantum mechanical system is finite, so in that case the concepts of entropy and information can be carried over from information theory directly. 

For classical mechanics, the same logic doesn't really work because in a classical system with a finite volume, the number of states is still infinite. In this case, physicists have to define a unit of entropy as a volume of space space so that it gives roughly the same answer as quantum mechanics for weakly interacting systems with large numbers of particles. This is ok because in classical physics only proportions of energy differences matter, so the definition of some unit of entropy always ends up canceling out. 

## Entropy and Time's Arrow 

Entropy is the fundamental concept in physics that is associated with a direction of time that distinguishes past from future. 

## Measurability of Entropy

Entropy is not a measurable quantity but rather a theoretical one that we ascribe to systems based on our theoretical knowledge of them. If we were to ascribe a certain value $S$ of entropy to a system, this value would be an inference based on our idea about how many states a sytem can actually have for given values of energy and possibly other observable quantities. Suppose, for example, that you cleaned your room. It would be possible to estimate the change in entropy of the room by attempting to enumerate the number of clean states in relation to messy states, but this would not be a measurement. It would be a theoretical result that would depend on an accurate understanding of all possible configurations of matter in the room. 

Differences in entropy are sometimes measurable. In particular, observations about how the temperature of a system changes in response to changes in heat energy tell us about changes in entropy. It is possible that other experiements can tell us about other entropy differences, but it is in the context of heat and temperature that entropy is best understood. 

In real systems, there can always be hidden order that is not understood. Think of someone you probably know whose desk alawys appears to be in a state of chaos but who never has trouble finding where anything is. His desk is therefore more ordered than it appears. If you rearranged his desk, he would not be able to find anything. Thus, two configurations that are apparently similar are actually not similar, and can be distinguished by asking your friend if his desk is messy. Thus, some idea about how much entropy a system has can change as a result of a deeper understanding of the system resulting from some new scientific investigation of it. 

### The Second Law of Thermodynamics

If entropy is not disorder and is not measureable, what does the second law of thermodynamics mean? This law states 

2. **In a closed system, the entropy never decreases.**

I said above that a more disordered state has more entropy than an ordered state, so this law does mean that disorder always increases. However, given that entropy is not measurable, this law is certainly of a different character than the law of gravity or even the first law of thermodynamics, which states 

1. **Energy is conserved.**

These laws can be tested empirically, whereas the second cannot. If entropy is an explanation for disorder in phsyics, the second law is a tautology becasue if entropy decreased, that would indicate that some process had occurred which can only happen backwards in time. 

When entropy was first described, physicists inferred its existence but did not understand what it was. Plank, for example, believed that entropy was a fundamental quantity like energy that would eventually be observed directly. However, he was disappointed when Boltzman was able to explain it as emerging out of statistical mechanics because he wanted to be working on fundamental laws, not emergent quantities. Before Boltzman's work, physicists did not understand entropy as relating to disorder. Instead, entropy was understood as a quantity whose increase expressed irreversibility in physics. 

The second law of thermodynamics is certainly a deep and important principle that is at the heart of everything in our experience, but it is not a law of physics in the ordinary sense. It is closer in character to something like praxeology than to other laws of physics because it has to do with ideal things like value that we ascribe to the world but cannot observe. 

## Entropy as the Foundation of Thermodynamics

### Temperature in Terms of Entropy


Temperature does not measure something that can be easily identified concretely. The relationship between heat energy and entropy is different for every substance. For ideal gasses, temperature is proportional to the average kinetic energy of a particle in the gas. Although real gasses are not ideal, this relation explains why why some gases are stronger greenhouse gasses than others. Gasses with more comlpex molecules store more of their internal energy as potential energy, and hence have higher heat capacities. carbon dioxide is a stronger greenhouse gas than oxygen, and why methane is stronger than carbon dioxide. Stronger greenhouse gasses store more energy at a given temperature than weaker gasses, and are thus at a higher temperature when they radiate the same amount energy into space that they absorb from the sun. 

The zeroth law of thermodynamics, which was added later, states 

0. **Bodies that are in thermal equilibrium with one another have the same temperature.**

Thus, temperature is measured by allowing a thermometer to come into equilibrium with the substance being tested. At equilibrium, the substance is giving as much energy from its interaction with the thermometer as the thermometer is giving back to it. This information is enough to guess at the relationship between temperature and entropy. 

Two bodies which are at thermal equilibrium with one another should not be able to increase their total entropy by transferring energy from one body to another. Thus the number of states in each body must be increasing with regard to increases in energy at the same rate. If the number of states in one body is increasing faster with regard to increases in energy than the other, than we would expect energy to move into that body from the other and we would say that it has a lower temperature. 

which turns out to be correct. 


## Thermal Equilibrium 

In theoretical physics today, entropy is considered to be a more fundamental idea than temperature. Originally, temperature was defined in terms of thermometers and entropy was defined as in terms of temperature via the integral version of the expression above. 

Nowadays, temperature is defined in terms of entropy. However, there is a big difference between temperature as measured in a thermometer and temperature as a function of entropy. The difference is that a real thermometer will always measure a temperature whereas the theoretical definition only exists in thermal equilibrium. 

The idealization of thermal equilibrium is the reason I say that entropy cannot be measured in real systems. One can measure temperature but one cannot make inferences about entropy without knowing that the measurement is taken at thermal equilibrium. But we cannot know that we are at thermal equilibrium without an exact knowledge of the system in question, which we only have of theoretical systems, not real ones. You can of course watch a system and observe that it has not apparently changed in a while, but there could always be some very slow reaction going on that is not evident over your observational time scale. 

For exmaple, imagine a system of two gasses that were mixed together but which interacted only weakly. One gas could be hot and the other cold. A thermometer would measure a temperature if it was 

For example, suppose that the proton decays, as many theoretical physicists suspect. That would mean that there are unknown states that are not being accounted for that are not being occupied by any energy added to some system consisting of ordinary matter. Any measurement of the temperature of ordinary matter would have to be less than the theoretical temperature defined in terms of entropy. 

In the example above, the measured temperature would give us a good idea of the entropy. 

## The Third Law of Thermodynamics

The third law of thermodynamics states 

3. **As the temperature approaches absolute zero, the entropy approaches a constant value.**

This can be understood by transforming the differential expression above into an integral expression:

$$ S = \int \frac{d E}{T} + C $$ 

The constant at the end of the integral expression is necessary to set the entropy at absolute zero, which is different for different materials. Two different systems at absolute zero may have different entropies because a system may have one or more lowest energy states. If there is one lowest state then the entropy at absolute zero ought to be zero because there is no ambiguity about which state it is in, whereas if there are more than one, it ought to be greater than zero. 

## Entropy and Life 

Some processes, an in particular the evolution of life, appear to contradict the idea that there is always a tendency toward more disorder. 

Consider a lion. The lion is a very ordered system. Or is it? The whole lion system is not merely the body of the lion but also the zebras that it eats. Without them, the lion system could not stay ordered. Thus, a lion maintains its own order but destroys the order of many zebras. In the net, the lion system maintains order inside its own body by creating a great deal more disorder outside its body. All life works this way. 

If you consider that all life is driven by the fire in the sun, the total entropy being created there is enormous in comparison to anything going on on the Earth. 

Statistical Physics of self-replication

## Entropy and Quantum Gravity

Quantum information conjecture
