# QuantumVibes: Interactive Quantum Mechanics Simulator

**[>>> Click here to play QuantumVibes in your browser! <<<](https://tront.xyz/quantumvibes/)**

---

So, yeah. Quantum mechanics. It's one of those things that always tickles the back of your brain if you're a dev, right? You think you kinda get it. Double-slit, Schrödinger's cat, all that jazz. But then, every once in a while, something just re-scrambles your eggs in the best possible way.

For me, recently, it was a damn good [**Veritasium video about really trusting quantum mechanics**](https://www.youtube.com/watch?v=qJZ1Ez28C-A). I'd *known* about Feynman's path integrals – the idea that a particle takes *every possible path* simultaneously. But seeing it visualized so clearly... it wasn't just an abstract concept anymore. It was like, "Oh. OH. Light is literally exploring *all the goddamn paths*." That hit different.

*(Image Placeholder: Feynman's Infinite Paths concept - will be added later)*

And when my brain breaks like that, I gotta build. So, **QuantumVibes** was born – a quick, dirty, browser-based interactive toy to poke at this weirdness. Popped into existence around early May 2025 after some chats and that video rattling around in my skull.

## The "Vibecoding" Process: Yelling at a Robot Until Physics Happens

Now, how do you make a quantum sim on a whim when your main jam is C# and Unity, but you want this sucker on the web? You "vibecode" it. You sit down with an AI – Gemini, in this case – and you start prompting. And prompting. And occasionally cursing.

Let's be real: the effort was probably **1% me and 99% the robot**. I did some HTML nudging, but the JavaScript core? That was a collaborative hallucination. Took around **30 solid "shots"** (prompt iterations) to get something resembling the vision. And yeah, once Web Workers got involved for performance, I had to nuke the AI's context and start a fresh chat. It gets... *confused*. Standard procedure for anything non-trivial.

> Is it elegant code? Probably not. Does it work and let you fiddle with quantum concepts? You bet. That's the chaotic beauty of vibecoding.

---

## QuantumVibes: Two Flavors of Mind-Bending

The toy has two main modes:

### 1. The Double-Slit Experiment: Wave? Particle? Yes.

*(Animated GIF/Image Placeholder: Double-Slit Simulation - will be added later. Link to live demo for now.)*
**[See the Double-Slit in Action (Live Demo)](https://tront.xyz/quantumvibes/)**

The classic that gives everyone an existential crisis. My sim lets you:

*   Switch the "Observer" on/off.
    *   **OFF:** Wave behavior, iconic interference patterns.
    *   **ON:** Particle behavior, two clumps, no interference. The act of "observing" (which in my sim gives the particle a random kick) changes everything.
*   See the results FAST. I abused Web Workers to fire off like 10,000+ "particles" at high speed to build that detector histogram almost instantly. The particles you see flying on the main thread? Mostly eye-candy.
*   Fiddle with sliders: `Slit Separation`, `Slit Height`, `Wave Constant` (your effective wavelength!), `Particle Speed`, etc.

**Accuracy disclaimer:** It's a *demonstration*. It shows the *effect*. It's almost certainly not Nobel Prize-winning physics in its mathematical rigor. But the diffraction patterns look cool, and it gets the core idea across.

### 2. Feynman's Path Integral Explorer: Taking ALL The Roads

*(Animated GIF/Image Placeholder: Path Integral Simulation - will be added later. Link to live demo for now.)*
**[Explore Path Integrals (Live Demo)](https://tront.xyz/quantumvibes/)**

This is where that Veritasium video really shines through in the project. You set start (A) and end (B) points. The sim then draws a zillion random paths between them. The ones closest to the "path of least action" (usually the straightest) are emphasized. It's wild to see the classical path emerge from the quantum fuzz.

---

## The "Aha!" Moment & Wrapping Up

That Veritasium video just framed the "all paths" idea in a way that made it *click* visually and intuitively for me. My little sim is a tribute to that. It's one thing to read that a particle explores every route; it's another to *see* a representation of that, even a simplified one, and watch order emerge from apparent chaos.

This was a quick, fun, slightly unhinged project. Mobile experience is probably janky. Accuracy is "good enough for jazz." But if it makes one other person go "whoa, quantum stuff is weirdly cool," then mission accomplished.

---

## Try It Out!

Go on, [**play with QuantumVibes**](https://tront.xyz/quantumvibes/). Break it. Stare into the quantum abyss. You know you want to.

## Join the Discussion

And if you wanna talk shop – gamed
