## Research Theme 1 — Search Intent
Research Question

Why do people choose search instead of navigation?

Purpose

Investigate the cognitive and situational factors that influence a person's decision to search rather than navigate through an information system.

Areas of Investigation

Potential research questions include:

When do users decide to search?
What types of goals encourage search?
How does prior knowledge influence search behaviour?
What role does uncertainty play?
When is navigation preferred over search?
How do urgency and task complexity influence behaviour?
Potential Evidence Sources
Human-Computer Interaction
Information Retrieval
Information Seeking Behaviour
Cognitive Psychology
Library & Information Science
Candidate Concepts

Possible recurring concepts may include:

Goal-Oriented Behaviour
Information Seeking
Task-Oriented Search
Exploratory Search
Known-Item Search
Uncertainty Reduction

Evidence Review — Search Intent

1. Search is Goal-Oriented

This is probably the strongest and most consistent finding we'll encounter.

People generally don't search because they enjoy searching.

They search because they have a goal they want to achieve.

Examples:

Complete a task.
Solve a problem.
Verify information.
Answer a question.
Continue a process.
Reduce uncertainty.

The search itself is merely a means to an end.

2. Search Begins with an Information Need

This is one of the foundational ideas in Information Seeking Behaviour.

Something creates a gap between:

What I know

and

What I need to know.

That gap motivates search.

Sometimes it's curiosity.

Sometimes it's urgency.

Sometimes it's frustration.

Regardless of the trigger, search begins because a person recognises that gap.

3. Search is Chosen When the Destination is Known (or Believed to Be)

This is where navigation and search begin to diverge.

Navigation is often exploratory.

Search is often intentional.

Examples:

Navigation:

"Show me what's available."

Search:

"Take me to X."

That distinction appears repeatedly throughout HCI literature.

4. Prior Knowledge Shapes Search Strategy

Experts and novices rarely search the same way.

Experts:

Know terminology.
Know categories.
Recognise concepts quickly.

Novices:

Use descriptive language.
Ask questions.
Search using symptoms rather than names.

This has enormous implications for the Codex.

5. Uncertainty Drives Search

This one particularly interests me.

People don't search because information exists.

They search because uncertainty exists.

Search is essentially an attempt to reduce uncertainty.

That observation appears to connect beautifully with several topics we've already researched.

## Research Theme 2 — Search Formulation
Research Question

How do people translate what they want into search queries?

Purpose

Investigate how people express information needs using language, keywords, concepts, and mental models.

Areas of Investigation

Potential research questions include:

How are search queries formed?
How does vocabulary influence search success?
How do people search when they lack correct terminology?
How do users refine searches?
How do experience and expertise affect query formulation?
What happens when users cannot clearly describe what they need?
Candidate Concepts

Possible recurring concepts may include:

Mental Models
Vocabulary Mismatch
Query Reformulation
Concept Recognition
Terminology Translation
Natural Language Search

## Research Theme 3 — Search Feedback
Research Question

How do people evaluate whether a search system understood their intent?

Purpose

Investigate how search results communicate relevance, build trust, and help users continue their search journey.

Areas of Investigation

Potential research questions include:

What information should search results contain?
What makes a result appear trustworthy?
How do users recover after unsuccessful searches?
What encourages users to refine rather than abandon a search?
How should systems communicate uncertainty?
How much context helps users judge relevance?
Candidate Concepts

Possible recurring concepts may include:

Relevance Judgement
Trust Signals
Result Context
Error Recovery
Progressive Refinement
Search Confidence

## Emerging Observation

Current research suggests that search may function as the interaction point between a user's internal knowledge state (goals, uncertainty, prior knowledge, mental models) and the Codex's knowledge system (information architecture, navigation, presentation, and intelligent tools).

Further research should investigate whether the primary outcome of effective search is the reduction of uncertainty, and whether this concept consistently emerges across Information Seeking Behaviour, Human-Computer Interaction, Cognitive Psychology, and Information Retrieval literature.

## Research Theme — Language & Expression
Underlying Research Question

How do people translate an internal idea into external language?

Why this question matters

Before a person types anything into a search box, something has already happened.

They've recognised an information need.

They've formed a mental representation of what they're looking for.

Now they have to communicate it.

That sounds simple, but cognitively it's actually a surprisingly complex process.

A user doesn't search with knowledge.

They search with their current understanding.

Evidence Review

Looking across Cognitive Psychology, Information Retrieval, Human-Computer Interaction, Psycholinguistics, and Information Seeking Behaviour, several recurring ideas begin to emerge.

1. People search using concepts, not necessarily terminology.

One of the strongest recurring observations is that people rarely begin with the "correct" vocabulary.

Instead, they begin with whatever concepts they currently possess.

For example:

Official terminology:

Carrack

User thinks:

Big boat

Or:

Official terminology:

Information Architecture

User thinks:

Organising information

The person isn't wrong.

They're simply describing the concept through their existing mental model.

Emerging Observation

People appear to formulate searches using the language available within their current understanding rather than the language used by the information system.

2. Language reflects mental models.

This is something I think we'll see repeatedly.

Words are not just labels.

They reveal how someone conceptualises a problem.

Consider three searches:

Teleport

Magnus

Fast travel

All three may refer to the same system.

Yet each reveals a different mental model.

One focuses on the function.

One knows the official name.

One compares it to another game.

The search query becomes a window into how the person currently understands the world.

Emerging Observation

Search queries may communicate a person's mental model as much as their information need.

3. People minimise effort when expressing themselves.

This connects beautifully with Recognition vs Recall.

People naturally choose words that require the least effort to remember.

Instead of searching:

Ornette's Spirit Essence

Someone searches:

infinite pot piece

That's cognitively cheaper.

Emerging Observation

People tend to formulate search queries using language that minimises cognitive effort rather than maximises precision.

4. Vocabulary is socially constructed.

This one surprised me when I first started reading about information behaviour years ago.

People don't develop vocabulary in isolation.

They learn it from:

Communities
Friends
Streamers
Guilds
Reddit
Wikis
Official documentation

Different communities often develop completely different names for the same thing.

For Sovereign, that's incredibly important.

Emerging Observation

Search vocabulary is influenced by social and community language, not solely by official terminology.

5. Expression changes as expertise grows.

This connects directly back to Knowledge States.

A beginner may search:

better horse

An experienced player searches:

T10 Doom

The underlying goal may be similar.

The language reflects experience.

That means language itself can become an indicator of someone's current knowledge state.

Emerging Pattern

I noticed something interesting when arranging these observations.

Information Need

↓

Mental Model

↓

Available Vocabulary

↓

Search Query

The search query isn't the beginning.

It's the output of several cognitive processes.

Candidate Evidence-Based Concept

I wouldn't validate this yet, but I think the evidence is starting to point towards something like:

People formulate search queries by expressing their current mental model using the vocabulary available to them, rather than necessarily using the terminology of the knowledge system.

That single statement seems to explain:

novice language
expert language
synonyms
colloquial terms
abbreviations
descriptive searches
terminology mismatch

without being tied to a specific technology.

Implications for Sovereign (Observation Only)

This is where I think we need to resist jumping into implementation—but it's hard not to see the possibilities.

If the evidence continues to support this concept, then the Codex shouldn't expect users to speak its language.

Instead, it should strive to understand the user's language.

That doesn't necessarily mean AI. It could influence search indexing, aliases, redirects, glossary design, metadata, or future intelligent tools. The implementation is still an open question.


## Theme 3 — Adaptation

Stage 1 — Relevance Assessment

These questions are about the user's first impression.

How do people judge whether a search result is relevant?
What information helps users decide which result to choose?

Underlying question:

How do users recognise that a result appears to match their intent?

This will almost certainly connect back to:

Information Scent
Recognition vs Recall
Scanning Behaviour

We've already researched those.

Stage 2 — Confidence Assessment

Now the user has noticed a result.

Next comes trust.

How much context is needed before users trust a result?

I actually think this question belongs here because users aren't asking:

"Is this true?"

They're asking:

"Do I believe this is what I need?"

That's a confidence judgement.

Stage 3 — Failure Recognition

Now imagine the system got it wrong.

These questions explore that moment.

How do users decide that a system has misunderstood them?
What makes users abandon a search?

Notice the order.

People don't abandon immediately.

They first recognise a mismatch.

Stage 4 — Recovery

This is where learning happens.

What encourages users to refine rather than give up?
How do users recover after unsuccessful searches?

This is fascinating because it transforms failure into another learning opportunity.