# COMPSCI1__Paper_ComputerScience_FieldRename__public

-+-

# The Case for Computational Systems Science

*A position paper on renaming the field of computer science*

## 1. Introduction

Names are not neutral. They tell a newcomer what a discipline is about, tell a funder what it is worth paying for, and tell a department which hires and courses belong inside its walls. Over time, a name also tells the people inside the field what they are allowed to think of themselves as doing.

The name "computer science" was coined when the computer was a rare, room-sized object and the main question was how to make it do arithmetic faster and more reliably. That was a sensible name for that moment. This paper argues that it no longer describes the field, that the mismatch has real costs, and that the discipline should adopt a new name: **Computational Systems Science**.

The argument has four parts. First, the object of study has changed, and the old name points at the wrong thing. Second, the new name is more accurate on each of its three words. Third, a name that fits will improve teaching, hiring, and public understanding in concrete ways. Fourth, the strongest objections to renaming deserve honest answers, and I offer them.

## 2. A name that points at the wrong object

A well-known quip holds that computer science is no more about computers than astronomy is about telescopes. It was meant as a joke, but it contains a real diagnosis: the field's best ideas were never about the machine. They were about procedure, structure, limits, and the nature of information. The machine was the instrument, not the subject.

For decades the quip was easy to shrug off, because the instrument and the subject sat close together. Today they have come apart entirely. Computation now runs inside thermostats, insulin pumps, shipping containers, stock exchanges, power grids, hospital scheduling systems, and the recommendation engines that shape what millions of people read each morning. Very little of this looks like a computer in the sense the name implies. There is no screen, no keyboard, and often no single place where the computation "lives."

What practitioners actually study and build are not computers but **systems**: many components, some written by hand and some learned from data, interacting with each other, with people, with institutions, and with the physical world. The interesting questions are about how these systems behave, fail, adapt, and can be held accountable. A name centered on the box misdescribes a field whose real subject is the web of things the box is connected to.

## 3. Why each word earns its place

### 3.1 "Computational"

The first word keeps what is distinctive and durable about the discipline: a precise, formal account of what can be computed, how efficiently, and with what guarantees. Computability, complexity, algorithms, and logic remain the intellectual core. Choosing "computational" rather than "computing" or "computer" shifts the emphasis from the artifact to the process. It also leaves room for computation that happens outside silicon, such as in biological cells, in markets, and in physical simulations, which the field increasingly engages with.

### 3.2 "Systems"

The second word is the one that does the new work. It says that the unit of analysis is a whole made of interacting parts, and that behavior often cannot be read off from the parts alone. This matches how modern software actually fails. Outages rarely come from a single wrong line. They come from the interaction of a retry policy, a cache, a deployment schedule, and a surge in demand that nobody modeled.

It also matches how software increasingly gets built. A program no longer arrives as a finished text that one person can read end to end. It is assembled from libraries, services, pretrained models, configuration, and tools that act on the developer's behalf. Reasoning about such an assembly is systems reasoning: where are the boundaries, what are the assumptions at each interface, and what happens when one of them quietly changes.

Finally, "systems" is the word that lets people into the room. A sociologist studying how a scheduling algorithm reshapes a hospital ward, an economist modeling a platform's incentives, and a lawyer drafting rules for automated decisions are all studying computational systems. Under the current name, they are visitors. Under the proposed one, they are colleagues.

### 3.3 "Science"

The third word is deliberate, and it is a commitment rather than a decoration. Some will say that much of the field is engineering, and they are right about a good share of its daily work. But "science" signals that the discipline makes claims that can be tested, that it measures rather than merely builds, and that it is willing to be surprised by what its own creations do.

This matters most now. When a system's behavior is learned rather than written, nobody can simply read the source to know what it does. The only honest approach is empirical: form hypotheses about its behavior, design experiments, and report the limits of what was found. A field that sees itself as a science is better positioned to treat these systems with that kind of discipline than one that sees itself as a craft.

## 4. Why not a name built around AI?

It is tempting to rename the field after whatever is currently transforming it. I think this is a mistake, for three reasons.

**First, such names age badly.** Fields that tied their identity to a single technology have often been left holding a label for something that later became ordinary. A name should survive the next shift as well as the current one. "Systems" and "computational" have already survived several.

**Second, they are too narrow.** Learned models are one important class of component inside computational systems, alongside databases, protocols, sensors, human operators, and legal rules. A name that elevates one component above the whole distorts priorities, both in what gets taught and in what gets funded.

**Third, they invite the wrong self-image.** If the field names itself after a tool, it risks defining its job as using that tool. The more durable job is to understand and take responsibility for the systems the tools help create.

## 5. What a better name would change

Renaming is only worth the trouble if it changes behavior. I expect effects in four places.

**Curricula.** Programs built around "computer science" tend to organize themselves around the machine: architecture, languages, compilers, and operating systems, with everything else treated as an elective. A program built around computational systems would treat measurement, failure analysis, human factors, and governance as part of the core, because a system includes its operators and its consequences. Students would learn early that a correct algorithm placed in a badly understood system can still do harm.

**Hiring and promotion.** Departments hire in the shape of their name. A field that thinks of itself as the study of systems is more likely to hire and reward people who work on how deployed systems behave in practice, an area that is often treated as less prestigious than proving theorems or inventing new methods, even though it is where many of the hardest open problems now sit.

**Public understanding.** To most people, "computer science" suggests programming and gadgets. "Computational systems" suggests something closer to the truth: that the field concerns the structures that increasingly mediate banking, medicine, travel, and public life, and that those structures deserve scrutiny. A more accurate public picture would make it easier for citizens and regulators to ask informed questions, and harder for the field to claim that its outputs are merely tools with no consequences attached.

**Cross-disciplinary work.** Collaboration is easier when each party can see itself in the name. Fields like public health, urban planning, and ecology are already comfortable with the language of systems. Meeting them there lowers the cost of the joint work that the most pressing problems require.

## 6. Objections and replies

**"It is only a rebrand."** Names do not change reality by themselves, and a renamed department that teaches the same courses has gained nothing. But the history of academic disciplines shows that names and structures reinforce each other. Renaming is a signal that creates permission and pressure to change the substance. It is a necessary condition for some reforms, not a sufficient one, and I do not claim otherwise.

**"'Systems' already means something specific in computer science."** This is true: in many departments, "systems" is the name of a subfield covering operating systems, networks, and distributed computing. The overlap is real, and it is the most serious objection. I think it is manageable. The subfield can keep its name inside the larger discipline, much as "theory" and "languages" do. And the overlap is partly a feature, since the subfield's habits of thinking about failure, scale, and interfaces are exactly what the wider discipline needs more of.

**"It is too vague."** Any broad name looks vague from outside, and "computer science" is hardly crisp. A discipline's definition comes from its practice rather than its label. What the proposed name offers is a direction: toward wholes rather than parts, toward behavior rather than code, and toward consequences rather than correctness in isolation.

**"The change would be disruptive and costly."** It would. Renaming departments, degrees, and journals takes effort and creates short-term confusion. The question is whether the benefit exceeds the cost, and a gap between a field's name and its reality does not close on its own. It grows as the field changes. Paying the cost earlier is cheaper than paying it later.

**"Theory will be marginalized."** The word "computational" is placed first on purpose. Formal foundations are what make the study of systems rigorous rather than anecdotal, and nothing in the proposal diminishes them. If anything, systems built from components that nobody fully understands make the demand for sound theory stronger.

## 7. How the change might actually happen

Disciplines rarely rename themselves by decree. More often, a new name appears first in a few forward-looking programs, then in journal titles and conference tracks, and eventually in the way funding bodies draw their categories. A practical path might look like this:

- Begin with new degree programs and research centers that adopt the name and demonstrate the curriculum behind it.
- Encourage existing conferences to add tracks on the behavior and governance of deployed systems, which gives the new scope a venue.
- Let departments adopt the name when their actual content has caught up, so the label never runs ahead of the substance.

This gradual route also tests the idea. If the name attracts good students and productive collaborations, it will spread. If it does not, we will have learned something about what the field actually needs.

## 8. Conclusion

The name "computer science" was an accurate description of a discipline organized around a particular machine. That machine has dissolved into the fabric of daily life, and the discipline's real subject has become the interacting, evolving, partly learned systems built on top of it, along with the people and institutions they touch.

"Computational Systems Science" names that subject. "Computational" keeps the rigor that defines the field. "Systems" turns attention to wholes, interactions, and consequences, and opens the door to the disciplines the work now depends on. "Science" commits the field to testing its claims and to being honest about what its creations do.

A name cannot do the work of reform. But a name that describes the present, rather than the past, makes that work easier to begin and harder to avoid. It is time for the field to call itself what it has become.