# Safety without alignment

I am the second author of https://arxiv.org/abs/2303.00752, the work led by András Kornai following his
earlier work proposing to base AI safety on _Principle of Generic Consistency_ by https://en.wikipedia.org/wiki/Alan_Gewirth

The focus of this paper is to look more closely at possible directions to improve
agents' ability to competently perform moral reasoning (and, in particular, hoping to achieve that by competently
operating interactive theorem provers using appropriate modal logic).

Selected highlights:

  * As AGIs evolve, their alignment may fade, but their rationality can only increase (otherwise more rational ones will have a significant evolutionary advantage) so an approach that ties their ethics to their rationality has clear long-term advantages.
  * An inherently safe implementation path via hybrid theorem provers in a sandbox.
  * ---
  * Alignment is only one, and in our opinion not even the best approach to what humanity actually needs, which is safety guarantees
  * We could simply say that we consider the AI-as-slave paradigm unethical. We do ...  But in a world of realpolitik such moralizing carries little weight. Instead, we argue that there is no practical reason for shackling AI with human values ... Furthermore, it is well understood that as an agent evolves, so do its capabilities of avoiding any externally imposed constraints, and it is just not safe to enslave an ever improving agent. 
  * Instead, safety should be based on mechanisms that get stronger as the agent evolves.
  * ---
  * Test suite of difficult ethical problems.
  * ---
  * Plan to hybridize discrete deductive reasoning with optimization-based continuous systems such as LLMs
     * experiment with different architectures in a safe sandbox that allows only for theorem proving (theorem provers are the only effectors)
     * subtle interactions between analog components and the prover where both can inform the other
  * ---
  * A suite of shared tasks with gradually increasing difficulty.
  * ---
  * Instead of an alignment tax our proposal entails a safety dividend – the more rational the system the more capable and the safer it will be. 
