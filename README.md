# Compression and Fidelity

### The two protocols of cultural transmission, and the law that decides which ideas, shapes, texts and institutions survive the trip

*A companion to [The Mountain and the Headband](https://github.com/ericrenone/The-Mountain-and-the-Headband-1985), [The Compression Instinct](https://github.com/ericrenone/The-Compression-Instinct), [Two Dots and a Smile](https://github.com/ericrenone/Two-Dots-and-a-Smile-Jobs-Toriyama-and-the-Design-Lineage-of-Emoji), [From Stone Monkey to Saiyan](https://github.com/ericrenone/From-Stone-Monkey-to-Saiyan-Wu-Cheng-en-Journey-to-the-West-and-Akira-Toriyama), and [The Soft Power of Japan](https://github.com/ericrenone/The-Soft-Power-of-Japan).*

---

**Abstract.** Every message is larger than the channel that carries it. A culture that wants an idea, a story, a shape or a rule to survive transmission across distance, time, language and indifference has exactly two strategies. It can protect the whole object and pay for the protection with reach: this is the *fidelity protocol*, and it requires an institution. Or it can reduce the object to the fewest marks that still carry its identity and let the receiver rebuild the rest: this is the *compression protocol*, and it requires only a receiver. The two strategies trade control for reach along a frontier that information theory described in 1948 and that evolutionary biology rediscovered in 1971, and every durable cultural system in the historical record turns out to run both at once: a compressed *kernel* that travels and a high-fidelity *archive* that does not. Systems with only an archive stop spreading. Systems with only a kernel degrade past a threshold and begin to betray their source. The framework is built here from information theory, replicator dynamics and the epidemiology of representations, then tested against scripture, political speech, music, logos, writing systems, sport, food, software standards, printing, and the two Japanese cartoonists who, between 1984 and 2026, ran the cleanest controlled experiment in the record: one chose compression and ended up as a gesture performed by presidents; the other chose fidelity and ended up as an institution honored at Cannes. Both were right. Neither could have survived alone.

---

## Contents

1. [The Problem: Every Message Is Larger Than Its Channel](#1-the-problem-every-message-is-larger-than-its-channel)
2. [Definitions](#2-definitions)
3. [The Mathematics and the Biology](#3-the-mathematics-and-the-biology)
4. [Scripture](#4-scripture)
5. [Words](#5-words)
6. [Sound](#6-sound)
7. [Shapes](#7-shapes)
8. [Rules](#8-rules)
9. [Food](#9-food)
10. [Print, and the Archive's Revenge](#10-print-and-the-archives-revenge)
11. [The Japanese Experiment](#11-the-japanese-experiment)
12. [The Laws](#12-the-laws)
13. [Failure Modes](#13-failure-modes)
14. [The Case Table](#14-the-case-table)
15. [A Decision Guide](#15-a-decision-guide)
16. [Limits and Counterexamples](#16-limits-and-counterexamples)
17. [Sources](#17-sources)

---

## 1. The Problem: Every Message Is Larger Than Its Channel

In November 1863, two men spoke at the dedication of a cemetery in Pennsylvania. Edward Everett, the most celebrated orator in America, spoke for about two hours. Abraham Lincoln spoke for about two minutes, in roughly 270 words. Everett's speech was more complete, more learned, more faithful to the facts of the battle. Nobody can quote a sentence of it. Lincoln's speech is carved into a wall in Washington and memorized by schoolchildren who cannot find Gettysburg on a map.

The usual lesson is that brevity wins. That is not quite it. Everett's speech lost not because it was long but because it was built for the channel it was delivered in, a crowd on a hillside with an afternoon to spend, and that channel ceased to exist the moment the crowd went home. Lincoln's speech was built for a narrower channel, a newspaper column, a schoolroom, a memory, and so it survived every channel that followed.

This is the general problem. A thing worth transmitting (a doctrine, a melody, a hero, a recipe, a rule of play, a protocol for computers) always contains more information than the channel it must cross: more than a child's memory can hold, more than a translator can carry, more than a 12-by-12 pixel grid can show, more than a three-second video clip can convey, more than a stranger's glance will tolerate. The sender has two choices and only two. Either make the channel carry the whole thing, which means building something to guard the whole thing, or make the thing small enough to fit, which means deciding what to throw away.

This document is about those two choices, what each one costs, who has made each one across the historical record, and why the systems that last make both.

---

## 2. Definitions

**Fidelity protocol.** The object is transmitted whole or not at all. Alterations are forbidden or punished. The protocol requires an *institution*: a church, a guild, a studio, a standards body, a court, a family of hereditary performers, a label of origin, because someone must hold the reference copy and have the power to reject deviations. Fidelity buys cumulative knowledge (the reference can be built on), prestige (the reference can be honored) and trust (the receiver knows what they are getting). It pays in reach, because every channel too narrow for the whole object is closed to it.

**Compression protocol.** The object is reduced before transmission to the subset of marks that carries its identity, and the receiver reconstructs the rest from their own resources. Alterations by the receiver are expected and tolerated. The protocol requires no institution, only a receiver with the capacity to fill gaps, which every human has. Compression buys reach (any channel that can carry the kernel can carry the object), speed and resilience to mistreatment. It pays in control: the sender does not decide what the receiver rebuilds, cannot collect credit or revenue from the reconstructions, and cannot stop the kernel from drifting.

**Kernel.** The compressed form: the minimum set of marks from which the identity of the object can be recovered by a receiver. A silhouette, a four-note motif, a one-sentence creed, a gesture, a logo, a tale type, a 17-rule game. Kernels tend to be *pre-linguistic*: contours, rhythms, faces, movements, which need no instruction to be recognized.

**Archive.** The high-fidelity form: the complete object, held by an institution, from which the kernel was cut and against which drift can be measured. A critical edition, a master recording, a sacred text in its original language, a reference implementation, a protected recipe, a film with no cuts. Archives tend to be *learned*: they require literacy in a vocabulary.

**The frontier.** For any object and channel there is a curve relating how much of the object is preserved to how far it can travel. Moving along it, you trade control for reach. You cannot be off the curve: no choice gives maximum fidelity and maximum spread at once for a fixed channel. Widening the channel (printing, broadcast, the internet) moves the whole curve outward, which is why the tradeoff seems to vanish during technological transitions and then reappears when the scarce resource shifts from bandwidth to attention.

**The threshold.** Below some level of fidelity, a kernel no longer recovers its source; it recovers something else. The receivers rebuild a different object and call it by the old name. This is the point where compression stops transmitting and starts replacing.

**Idiom.** What a kernel becomes once enough receivers have rebuilt it: a shared visual or verbal language in which new objects can be made by people who never saw the original. Credit for an idiom accrues to the compressor, not to the source and not to the implementers.

---

## 3. The Mathematics and the Biology

The frontier is not a metaphor. Claude Shannon's 1948 paper established that any source has an entropy, a floor below which it cannot be encoded without loss, and that a lossless code can approach that floor but not pass it. That is the mathematics of the fidelity protocol: there is a minimum size for the whole thing, and the channel must be at least that wide. Shannon's later work on rate-distortion theory, formalized in 1959, supplied the mathematics of the compression protocol: for any permitted level of distortion there is a minimum rate, and the curve relating the two is convex, so the first bits thrown away cost almost nothing and the last bits cost everything. Andrei Kolmogorov's 1965 definition of complexity as the length of the shortest program that reproduces an object gives the kernel its formal definition: the kernel is the shortest description from which a receiver can regenerate the thing.

Biology arrived at the same frontier from the other side. Manfred Eigen's 1971 work on self-replicating molecules showed that a replicator must copy itself with fidelity above a critical level, or the information it carries dissolves into noise across generations: the *error threshold*. But fidelity is not free, and a replicator with perfect fidelity cannot adapt. RNA viruses sit near the threshold on purpose, copying sloppily, mutating fast, spreading widely, and occasionally collapsing. The DNA of large organisms sits far above it, with proofreading enzymes, and changes slowly. The viral strategy is compression; the proofreading strategy is fidelity; and life uses both, in different places, at different times.

Richard Dawkins, extending the idea to culture in 1976, named three properties of a successful replicator: longevity, fecundity and copying-fidelity. Notice that fecundity and fidelity are in tension, which is the frontier again. Dan Sperber's 1996 account of cultural transmission as an epidemiology of representations added the decisive observation: human transmission is not copying at all. Each receiver reconstructs the representation from fragmentary input and their own prior knowledge, so cultural objects do not replicate, they *converge on attractors*: forms that are easy to reconstruct from little input. Frederic Bartlett had shown this experimentally in 1932, passing a Native American folktale through chains of English readers and watching it shed unfamiliar details and reshape itself toward a familiar schema within a few retellings. The kernel, in Sperber's terms, is an attractor; the archive is an attempt to resist attraction by force.

The oral-formulaic theory of Milman Parry and Albert Lord, published as *The Singer of Tales* in 1960, documented a civilization-scale solution. Homeric epic, transmitted for centuries without writing, was built out of metrical formulas and type-scenes, compressed units a singer could recombine in performance. The epic was never transmitted whole; it was transmitted as a kernel and a grammar, and each performance rebuilt it. Walter Ong's 1982 synthesis extended this to oral culture generally: what cannot be compressed into mnemonic form does not survive without writing. Writing, and then print, were the technologies that made the fidelity protocol possible at scale. Elizabeth Eisenstein's 1979 study of the printing press argued that its central gift was not reach but *fixity*: for the first time, two readers in two countries could be sure they were reading the same text, and cumulative science became possible because errors could be identified against a stable reference. Walter Benjamin had seen the other half in 1935: mechanical reproduction destroys the *aura*, the unique presence of the original. Benjamin was describing what the fidelity protocol loses when compression wins.

So the two protocols have a mathematical floor, a biological threshold, a psychological mechanism and a technological history. What follows is the record of people choosing between them.

---

## 4. Scripture

Religion is the oldest laboratory because religions are transmission systems that have been running, under observation, for millennia.

**The Vulgate and the vernacular.** The Western Church held its scripture in Latin for a thousand years. The Council of Trent in 1546 declared Jerome's Vulgate the authentic text, and the translation of scripture into the languages people spoke was, for long stretches, a capital offense: William Tyndale was strangled and burned in 1536 for putting the New Testament into English. This was the fidelity protocol enforced by an institution with the power to kill. It preserved the text. It also confined direct access to the text to those who could read Latin, which is to say the institution itself. Martin Luther's German New Testament of 1522 and the English Authorized Version of 1611 were compression events in the strict sense: the object was re-encoded for a narrower channel, the vernacular reader, and the Reformation that followed was, in transmission terms, the kernel escaping the archive. Protestantism spread in a century what the archive had held for ten.

**Koine.** The pattern is older than the Reformation. The New Testament itself was written not in the Attic Greek of Plato but in koine, the simplified common dialect that Alexander's conquests had spread across the eastern Mediterranean. The founding documents of the world's largest religion were composed, from the start, in a compressed language, because the intended channel was the marketplace, not the academy. Paul's letters strip the Mosaic law to a kernel that a gentile could carry; the Jerusalem church that kept the whole law did not survive the first century as a distinct movement.

**The Qur'an and the shahada.** Islam ran the opposite protocol on its text and the same protocol on its kernel, which is why it is the clearest case of a system doing both. The Qur'an is held to be the Qur'an only in Arabic; translations are conventionally titled as interpretations or "meanings," as in Pickthall's 1930 English version. Recitation is a disciplined art with a chain of transmission. This is fidelity at its most absolute. And yet Islam spread from Arabia to Indonesia and West Africa, among people who did not read Arabic, because its kernel is among the most compressed in religious history: one sentence of testimony, five daily prayers whose postures are identical from Dakar to Jakarta, and a set of gestures that need no translation. A Muslim can recognize another praying at a hundred meters by silhouette. The archive stayed in Mecca; the kernel went everywhere.

**The cross.** Christianity's kernel is a shape with two lines. It can be drawn in sand, made with a hand on the chest, cut into a gravestone, worn around a neck, and recognized by someone who has never read a page of scripture. It was adopted as the central symbol some centuries after the events, by which point the archive (the creeds, the councils, the canon) had been assembled by an institution. The order matters: the archive was built by fidelity and then issued a kernel for compression. The Nicene Creed, hammered out in 325 and 381, is an intermediate form, a compressed archive, a few hundred words designed to be recited by people who would never read the councils that produced them.

**Buddhism** ran the same dual protocol with a different accent. The Pali canon was preserved by monastic recitation with ferocious fidelity. The teaching that reached China, Korea and Japan was Mahayana, re-encoded in Chinese, and the form that reached the West in the twentieth century was Zen, which compresses the whole tradition into a posture, a breath and a paradox. Steve Jobs, as the companion essays show, received Buddhism as a kernel from a Sōtō priest in Los Altos and never read the archive. He got what the kernel carries: a standard of proof, not a doctrine.

---

## 5. Words

**Gettysburg.** Already told. Add the detail that Lincoln's text exists in five manuscript versions that differ in wording, and that scholars still argue over which he read. The kernel traveled; the archive is contested. This is the normal condition of a successful compression: the thing everyone knows is slightly different from any specific original.

**The Manifesto and Capital.** Karl Marx wrote two kinds of document. *Capital* is an archive: three volumes, the third assembled posthumously from notes, read in full by a small fraction of those who call themselves Marxists. The *Communist Manifesto* of 1848 is a kernel: a pamphlet, a few dozen pages, with an opening sentence about a specter and a closing sentence about chains that have been translated into nearly every written language on earth. Twentieth-century communist states ran the fidelity protocol on *Capital* (institutes, authorized editions, licensed interpreters) and the compression protocol on the *Manifesto* and, later, on Mao's *Little Red Book*, a pocket anthology of aphorisms printed in the hundreds of millions. The movement spread on the kernel and governed with the archive. When the archive's institutions collapsed in 1989–91, the kernel kept circulating, now detached from any state, which is what kernels do.

**"Survival of the fittest."** The cautionary case, and the clearest demonstration of the threshold. Darwin's 1859 argument runs to several hundred pages and never uses the phrase. Herbert Spencer coined it in 1864 as a compression of natural selection, and Darwin, under pressure from readers who found "selection" too deliberate a word, adopted it in the fifth edition of 1869. The four words traveled further than the book. They also recovered a different object: a tautology at best, and at worst a doctrine of social competition that Darwin's theory does not contain and that its author would have rejected. Receivers rebuilt the kernel into "the strong deserve to win," named the result Darwinism, and used it to justify things the archive forbids. This is what it looks like when compression crosses the threshold: the kernel is still called by the source's name, but it no longer recovers the source.

**Slogans and constitutions.** The French Republic's three nouns, the American Declaration's one sentence about self-evident truths, and the first words of the American Constitution are all kernels issued by documents that are archives. Nations, like religions, run both protocols: a founding text held by courts and scholars under a fidelity protocol, and a kernel of a few words that citizens carry without having read the text. A nation whose kernel detaches entirely from its archive (where the slogan is recited and the text ignored) is in the same condition as the "survival of the fittest" case, and the historical record suggests it does not end well.

---

## 6. Sound

**Four notes.** Beethoven's Fifth Symphony, first performed in 1808, is about thirty-five minutes of music that opens with a four-note motif. The motif is the kernel: it has been used as a Morse-coded "V" by the BBC in wartime broadcasts, as a ringtone, as a joke, as the whole symphony's name in common speech. The symphony is the archive, held in critical editions and performed by institutions that argue about tempo markings. The composer built the kernel on purpose; the entire first movement is a demonstration of how much can be reconstructed from four notes. This is the compression instinct as a compositional method.

**Bayreuth and Tin Pan Alley.** Richard Wagner built an opera house at Bayreuth in 1876 to control every variable of performance, and his heirs ran it as a fidelity institution for a century, with hereditary directors and a reference staging. The works are long, demand an orchestra of a hundred and a trained audience, and reach a few hundred thousand people a year. Tin Pan Alley, the New York song industry of the same decades, built three-minute songs for sheet music and later for the 78-rpm disc, a channel so narrow that a song had to carry its identity in a hook of a few bars. Nobody controls how a standard is performed; that is what makes it a standard. Wagner's archive is honored; the standards are sung. Jazz, which took the standards and rebuilt them nightly, is the oral-formulaic tradition reborn in a recording age: a kernel (the chord changes, the head) and a grammar (the idiom of improvisation), with no archive at all until recordings created one after the fact.

**MP3 and vinyl.** The MP3 standard, finalized in 1993, is a psychoacoustic compression: it throws away the parts of a recording the ear is least likely to notice, reducing files to roughly a tenth of their size. It won the first decade of digital music not because it sounded better but because it fit the pipe: a 56k modem, a 32-megabyte player, a shared hard drive. The vinyl revival and the lossless-audio market that followed are the fidelity protocol's counterattack: an archive sold as prestige to a minority. The two coexist, as the framework predicts, because they serve different channels: the earbud on the train and the listening room.

**Dubbing and subtitles.** The clearest modern experiment, because countries chose. Germany, Italy, Spain and France dub foreign films: the receiver re-authors the sound, and the film arrives compressed to its images, with a new voice. The Netherlands, Scandinavia and Portugal subtitle: the film arrives whole, with a strip of text. The dubbing countries reach larger audiences for foreign film and have historically had weaker English; the subtitling countries pay the "one-inch barrier" that the Korean director Bong Joon-ho named at the Golden Globes in 2020, and reach fewer viewers with a more faithful object. Studio Ghibli, which forbids cuts but permits dubs, has chosen the intermediate point: fidelity of image, compression of sound.

---

## 7. Shapes

Shapes are where the compression protocol is most legible, because a shape is a kernel that needs no language.

**The alphabet.** The deepest case. Pictographic writing preserves meaning per sign and demands thousands of signs; the Chinese writing system, a fidelity protocol maintained by an imperial bureaucracy and its examinations for two millennia, requires years to learn and carries meaning across dialects that cannot understand each other aloud. The alphabet, descended from Semitic scripts of the second millennium BCE, compresses writing to a few dozen signs that encode sound rather than sense, and can be learned by a child in a year. Alphabets spread with traders and conquerors; the Latin alphabet now writes more languages than any other system in history. The price was exactly the price the framework predicts: an alphabetic text is tied to one language's sounds and travels only as far as that language does, while a Chinese text can be read, after a fashion, by people who could not speak to each other. The companion essays' calligraphy teacher put the kernel's definition in one sentence: a letter is not a picture of anything.

**The bottle, the rings, the swoosh.** The Coca-Cola contour bottle of 1915 was designed to a brief that it should be recognizable in the dark, by touch, and when broken on the ground. The Olympic rings, drawn by Pierre de Coubertin in 1913, are five circles in five colors that can be reproduced with a compass by a child. The Nike swoosh of 1971 is a single stroke. Each is a kernel issued by a fidelity institution (a corporation with trademark lawyers, a committee in Lausanne) that guards the archive (the script, the charter, the brand book) with litigation. Corporate identity is the explicit, professionalized form of the kernel-and-archive structure: the logo travels; the brand standards manual stays home.

**The Slime, Totoro, the emoji.** The companion essays document three Japanese kernels in detail. The Dragon Quest Slime of 1986 is a teardrop with two dots and a smile, designed to be identifiable as a sixteen-pixel sprite, unchanged for forty years. Totoro, the forest spirit of 1988, is a closed contour with a wide mouth whose merchandise sustained Studio Ghibli for years. Shigetaka Kurita's 176 emoji of 1999 were drawn on a 12-by-12 grid at eighteen bytes each, and the ones that have survived every redesign are the ones with the fewest marks. The modern Apple emoji, drawn for a high-resolution screen, had to be redrawn in 2016 to display at larger sizes; the Slime has never been redrawn. A shape built for the narrowest channel survives every wider channel that follows, and a shape built for a wide channel dates the moment the channel changes.

**The empty face.** Scott McCloud's 1993 argument, refined by Neil Cohn's cognitive work in the 2010s, explains why the most compressed faces travel furthest: a face with two dots and a curve carries no one's identity and so can carry anyone's. The receiver supplies the rest, and what the receiver supplies is themselves. This is Sperber's reconstruction made visible. The Christian cross, the Olympic rings, the Slime and the yellow smiley of 1963 are all empty faces in this sense: maximal reconstruction from minimal input, with no institution able to control what is reconstructed.

---

## 8. Rules

Rules are kernels for behavior, and the history of games and standards is a history of which rulebooks fit through which pipes.

**Football and cricket.** The Football Association codified its game in London in 1863, and the Laws of the Game have numbered seventeen for most of their history. A ball, a flat space, two goals and the offside rule can be taught in an afternoon and played with a bundle of rags. The game spread along shipping routes, carried by British sailors, engineers and clerks, and took root wherever a port was: Buenos Aires, Genoa, São Paulo, Bilbao. Cricket, codified earlier, with a rulebook of dozens of laws, specialized equipment, matches lasting days and a vocabulary that must be learned, spread almost exclusively where the British state went: the colonies and dominions. Football follows the dub; cricket follows the alliance. The compressed game is now the world's; the faithful game is the Commonwealth's. Chess is the extreme of the compressed rulebook, a dozen rules yielding a game space no one has exhausted in fifteen centuries, which is why it crossed from India to Persia to the Arab world to Europe without an institution carrying it.

**The container.** Malcom McLean's 1956 shipping container is a kernel for logistics: a steel box of standard dimensions, formalized by the ISO between 1968 and 1970, that any crane, truck, train or ship in the world can handle without knowing what is inside. The compression is total. The box throws away every property of the cargo except its outer dimensions, and in exchange the cost of moving goods across oceans fell by an order of magnitude and world trade was rebuilt around it. The archive here is the ISO standard itself, held by a body in Geneva; the kernel is the box, handled by millions who have never read the standard.

**TCP/IP and OSI.** Through the 1980s two protocols competed to run the world's computer networks. The OSI model, developed by international standards bodies, was a seven-layer archive: complete, rigorous, specified in advance by committee, and never widely implemented. TCP/IP, which had grown out of working code on the ARPANET, was simpler, looser, and running. Jon Postel's robustness principle, written into the specifications in 1980, instructs an implementation to be conservative in what it sends and liberal in what it accepts, which is a compression protocol stated as engineering ethics: tolerate the receiver's reconstruction. Richard Gabriel's 1991 essay on why "worse is better" generalized the result: a simple, incomplete design that spreads will be improved by its users, while a complete, correct design that does not spread will not. The web repeated the experiment a decade later: HTML's forgiving parsers, which render broken pages, defeated the strict XML variants, which refused to.

**Unicode.** The exception that clarifies. Unicode, maintained by a consortium since 1991, is a fidelity institution: a single reference assignment of every character in every script to a number. Its product is the condition for compression everywhere else: because the archive is fixed, a kernel like a 12-by-12 emoji can travel from a Japanese phone to an American one and be rebuilt as the same character. This is the kernel-and-archive structure at the scale of the whole world's writing, and it shows that compression at the surface often depends on fidelity underneath.

**The metric system.** A kernel for measurement: a few base units and a decimal grammar, designed in revolutionary France to be learnable by anyone and adopted by nearly every country on earth. The archive is a platinum-iridium cylinder in a vault outside Paris, replaced in 2019 by a definition in terms of physical constants, which is to say the archive became a formula. Fidelity is now guaranteed by physics rather than by a locked door, which is the direction all archives tend over time.

---

## 9. Food

Food is a transmission system with an unusual property: the receiver always reconstructs it physically, with local ingredients, so the threshold is crossed constantly and visibly.

**Pizza.** Neapolitan pizza is governed by a fidelity institution, the Associazione Verace Pizza Napoletana, founded in 1984, which specifies the flour, the tomatoes, the oven temperature and the hand-stretching, and the art of the Neapolitan pizzaiuolo was inscribed by UNESCO in 2017. Pizza as a global object is the opposite: a flat bread with toppings, reconstructed in every country from whatever is at hand, with pineapple in Canada, corn in Japan, and a cardboard box in which the archive's constraints are entirely absent. The kernel (dough, red, cheese, round) spread to every country on earth; the archive stayed in Naples and became a certificate. Both exist. The certificate's value depends on the kernel's reach: no one would pay for authentic Neapolitan pizza if pizza were not already the world's.

**Sushi and the California roll.** Edo-period nigiri is a fidelity tradition with apprenticeships measured in years. The California roll, invented in the 1960s or 70s in Los Angeles or Vancouver (the claims conflict), inverts the rice to the outside to hide the seaweed from receivers who found it alien, and replaces raw fish with avocado and crab. It is a kernel reconstructed by the receiver's palate. It is also the reason sushi is a global category at all; the archive followed the kernel into countries the kernel had opened.

**Champagne and the appellation.** The European system of protected origin names (Champagne, Parmigiano-Reggiano, Roquefort) is the fidelity protocol codified in trade law: the name may be used only for the object made in the place by the method. The kernel ("sparkling white wine") traveled the world and is made everywhere; the archive is enforced by litigation. The appellation does not stop the kernel. It monetizes the archive. This is the mature form of the relationship: the institution stops fighting the compressed copies and sells the uncompressed original to those who can tell the difference.

---

## 10. Print, and the Archive's Revenge

It would be easy to read the record as a story of compression always winning. It is not. The largest single intellectual change in human history, the scientific revolution, was a victory of the fidelity protocol, and understanding why completes the framework.

Before print, every copy of a text was a reconstruction by a scribe, and errors accumulated with each generation; the manuscript tradition was a chain of Bartlett's retellings. Eisenstein's argument is that the printing press, from the 1450s, made *fixity* possible: a thousand identical copies, with the same diagram on the same page, so that a reader in Padua and a reader in Kraków could point to the same error and correct it. Tycho's tables, Vesalius's anatomy, and Newton's *Principia* of 1687 were archives that could be checked, and checking is what science is. Compression cannot do this. A kernel can be rebuilt by any receiver; that is its strength and exactly the property that makes it useless for cumulative correction, because no two reconstructions are the same object.

So the fidelity protocol is not the loser's strategy. It is the strategy of any system that needs to *accumulate* rather than merely *spread*. Science, law, engineering, and scripture-as-doctrine are fidelity systems, and they are the systems in which humanity's knowledge compounds. Kernels spread; archives grow. A civilization that has only kernels is an oral culture, rich in stories and poor in proofs. A civilization that has only archives is a priesthood, rich in proofs and unable to recruit.

And the archive issues its own kernels. Newton's *Principia* produced F = ma, three laws a schoolchild can recite; Einstein's 1905 papers produced E = mc², five characters on a T-shirt. Neither equation is the theory. Each is a kernel that the archive emitted so that the theory could travel to people who will never read it, and each recovers the theory well enough that a receiver who later opens the archive finds what they expected. That is the test of a good kernel: when the receiver finally reads the whole, it matches.

---

## 11. The Japanese Experiment

The companion essays document the case in full. Here it is restated as a controlled experiment, because it is the cleanest one in the modern record: two Japanese artists, born into the same industry, who launched their defining works within eight months of each other in 1984 and then chose opposite protocols for forty years.

**The compression arm.** Akira Toriyama, trained as a flyer designer, drew Dragon Ball for a weekly magazine that ranked every chapter by children's survey cards. He built his hero to survive mistreatment: plain clothes, a tail, a silhouette a child could copy, hair left uninked to save time that became the most legible power-up in comics. When the show was sold abroad, foreign broadcasters re-cut it, re-scored it, and in the United States replaced the entire soundtrack. He did not object. In 1986 he drew, for a video game, a monster that had to be recognizable at sixteen pixels, and produced a teardrop with two dots and a smile that has not been redrawn in forty years. He made one public appearance in the United States, hid behind a robot avatar, and said he never wanted to be a cartoonist.

**The fidelity arm.** Hayao Miyazaki and Isao Takahata founded Studio Ghibli in June 1985, the month a Los Angeles distributor released Miyazaki's *Nausicaä* in the United States with twenty-two minutes cut and the heroine renamed. They refused Western distribution for a decade, then signed with Disney in 1996 on condition of no cuts, and refused Miramax's request to trim *Princess Mononoke* for a lower rating in 1999. Miyazaki draws every frame, oversees every cut, and forbids computer animation above a small fraction of a film. He has refused to attend the Oscars over a war, called his own prime minister's constitutional plans despicable, and labeled his own films "cartoon films" to avoid the word anime.

**The results after forty years.** Toriyama's work became a gesture: the Kamehameha, performed by the Prime Minister of Japan and the President of France at a joint press conference in April 2026, two years after the author's death, and by tens of thousands in a Buenos Aires square the month he died. His shapes are on a Japanese prime minister's state gift (a kokeshi doll), a Chilean president's childhood (cited in a Tokyo speech), and the opening ceremony of the Tokyo Olympics (the Dragon Quest overture). Mexican city governments screened his show's finale in public squares in 2018 without a license, and the studio that owned it could only object. He received a French knighthood and a posthumous Hall of Fame induction. He is credited with inventing the poop emoji, which he did not draw; his comic set the idiom, and an anonymous designer drew the glyph.

Ghibli's work became an institution: a museum in 2001, a park in 2022, an honorary Palme d'Or in 2024 (the first ever given to a production company), a Princess of Asturias Award in 2026, two Oscars, a Golden Bear, and the longest-standing Japanese box-office record. Its films are not performed by presidents, because there is no empty space in them for a president to stand. And in March 2025 its style detached from it entirely, when an American company's image model let millions of people convert their photographs into Ghibli-like pictures without any Ghibli involvement, which is the kernel escaping an archive that had spent forty years refusing to issue one.

**The control variable.** Ghibli issued exactly one kernel, by accident: Totoro, whose merchandise, licensed in 1990, sustained the studio through years when its faithful films did not pay. Toriyama's work had exactly one archive, by accident: the Japanese magazine edition, which the companion essays treat as the reference against which every foreign re-cut is measured. Each arm of the experiment needed a little of the other protocol to survive, and got it without planning to.

**The state's role.** The Japanese government made neither. It arrived decades late, tried to originate soft power with a fund that lost 54 billion yen and was wound down in 2026, and succeeded only when it learned to *perform kernels it had not made*: a prime minister dressed as a video-game plumber at the 2016 Olympics, a comic-book striker painted on water trucks in Iraq in 2004, a gesture at a podium. The state could carry Toriyama's kernels because they are empty. It could only honor Ghibli's archive, because it is full, and it honored the archive while declining to quote the man who made it. Latecomers can wear kernels and fund archives. They cannot make either.

---

## 12. The Laws

**1. The channel decides the protocol.** Every transmission crosses a pipe narrower than the object. If the pipe can be widened (print, broadcast, the internet), fidelity becomes affordable. If it cannot (a child's memory, a translator, a glance, a sprite, a tweet), compression is the only option. Most of history's channels could not be widened, which is why most of history's durable objects are kernels.

**2. Reach and control trade off along a frontier.** For a fixed channel, no choice maximizes both. Fidelity systems keep control and lose reach (Bayreuth, cricket, the Vulgate, OSI). Compression systems gain reach and lose control (Tin Pan Alley, football, the vernacular Bible, TCP/IP). Technological transitions move the frontier outward and make the tradeoff seem to vanish; it returns when the scarce resource shifts from bandwidth to attention.

**3. Every durable system runs both.** A kernel that travels and an archive that does not. Islam has the shahada and the Arabic Qur'an. Christianity has the cross and the councils. Science has E = mc² and the paper. Apple has the icon and the hardware. Coca-Cola has the bottle and the formula. Ghibli has Totoro and the no-cuts policy. Systems with only an archive stop recruiting. Systems with only a kernel stop accumulating. The historical record contains no long-lived exception.

**4. Kernels are pre-linguistic; archives are learned.** The forms that survive the narrowest channels are silhouettes, rhythms, faces, gestures and a few words, because these are reconstructed by every receiver without instruction. The archive requires literacy in a vocabulary. The winning move, across every case, is to keep the learned layer conventional and put all originality in the pre-linguistic layer: Goku's story is a Chinese novel, Geneva is a redesigned Helvetica, the Gettysburg Address is in plain English, and the identity lives in the shape.

**5. The threshold is real, and crossing it replaces the source.** Below some fidelity, the receiver rebuilds a different object and keeps the old name: "survival of the fittest," *Dragonball Evolution*, a slogan recited by people who have never read the constitution it came from. The test of a good kernel is that a receiver who later opens the archive finds what the kernel promised. A kernel that fails this test is not transmitting; it is impersonating.

**6. Fidelity requires an institution; compression requires only a receiver.** This is why compression is cheap and fidelity is expensive, why archives are owned and kernels are not, and why a state, a church or a corporation can hold an archive but can only ride a kernel. An institution that tries to own a kernel (Toei in Mexico, DoCoMo refusing a glyph, Trent against Tyndale) is fighting the frontier and loses.

**7. Credit flows to the compressor; accumulation flows from the archive.** Toriyama is credited with the poop emoji he did not draw. Spencer's phrase is called Darwinism. The anonymous designer of the first mobile poop glyph is credited with nothing. Whoever reduces an object to its kernel owns the idiom, and the idiom is worth more than any implementation. But the knowledge that compounds, the proofs, the corrections, the laws, lives in the archive, and only an institution can keep it.

**8. The archive should issue its own kernel before someone else does.** F = ma, the cross, the Creed, the contour bottle, Totoro. An archive that refuses to issue a kernel will have one cut from it by strangers, and the stranger's kernel may cross the threshold. Ghibli's 2025 AI filter is the case: forty years of refusing to compress, and then a compression made without consent.

**9. Latecomers perform kernels; they do not originate them.** States, brands and institutions that arrive after a kernel has spread can wear it (Mario at Rio, the Kamehameha at the palace) or fund its archive (the Palme d'Or, the Person of Cultural Merit). Attempts to originate kernels by committee fail because kernels are selected by a number (a survey, a chart, ratings, sales, a children's ranking) and committees have opinions instead.

**10. Design for the worst channel; guard the best copy.** The operational rule. Build the kernel for the narrowest pipe the object will ever cross: the sixteen-pixel sprite, the one-bit screen, the 144-pixel grid, the three-second clip, the stranger's glance. Then hold one uncompressed copy somewhere an institution can defend it, and make sure the two still match.

---

## 13. Failure Modes

| Mode | What goes wrong | Cases |
|---|---|---|
| **Archive only** | The object is preserved and stops spreading; the institution becomes a priesthood | The Vulgate before Luther; OSI; Bayreuth's audience; Noh theatre under the hereditary schools; the Latin Mass after 1965, kept by a minority |
| **Kernel only** | The object spreads and stops accumulating; no reference exists to correct drift | Oral epic before writing; jazz standards before recordings; folk recipes; most internet memes |
| **Threshold crossed** | The kernel recovers a different object and keeps the name | "Survival of the fittest"; *Dragonball Evolution*; *Warriors of the Wind*; a slogan without its text |
| **Archive fights the kernel** | The institution litigates against its own reach | Trent vs. Tyndale; Toei vs. Mexican plazas; DoCoMo refusing a glyph that shipped anyway from a rival |
| **Kernel detaches** | The idiom circulates with no archive, no author and no owner | The 2025 Ghibli filter; the anonymous 1997 poop glyph; the Manifesto after 1991 |
| **Late origination** | A latecomer tries to make a kernel by committee | The Cool Japan Fund (¥54 billion lost, abolished 2026); most state-branded mascots; most corporate "viral" campaigns |
| **Wide-pipe complacency** | A kernel built for a wide channel dates when the channel changes | Apple's 2008 emoji rerendered in 2016; glossy icons after the flat-design turn; any identity that depends on resolution |

---

## 14. The Case Table

| Object | Kernel | Archive | Institution | Channel that forced the choice | Outcome |
|---|---|---|---|---|---|
| Christianity | The cross; the Creed | Scripture; the councils | The Church | Illiterate converts; the marketplace (koine) | Both protocols; global |
| Islam | The shahada; the prayer postures | The Arabic Qur'an; recitation chains | The ulama | Non-Arabic converts | Both; global |
| Buddhism | Posture, breath, koan (Zen) | The Pali canon | The sangha | Chinese and Japanese re-encoding | Both; pan-Asian, then global |
| Darwinism | "Survival of the fittest" | *On the Origin of Species* | Universities | Public debate | Threshold crossed |
| Marxism | The *Manifesto*; the *Little Red Book* | *Capital* | Party institutes | Workers; peasants | Both; kernel outlived archive |
| Gettysburg | 270 words | Five differing manuscripts | Libraries | Newspaper column; memory | Kernel won; archive contested |
| Beethoven's Fifth | Four notes | The score | Orchestras; editors | Memory; Morse; ringtones | Both |
| Popular song | The hook | The master recording | Labels | Sheet music; the 78; the MP3 | Compression; archive after the fact |
| Film abroad | Dubbed image | Subtitled whole | Distributors | National audiences | Countries chose differently |
| The alphabet | A few dozen signs | — | None needed | Traders; children | Compression; writes most languages |
| Chinese script | — | Thousands of characters | The examination bureaucracy | Dialects | Fidelity; cross-dialect reading |
| Coca-Cola | The contour bottle | The formula; the script | The corporation | Darkness; touch; broken glass | Both |
| Olympic rings | Five circles | The Charter | The IOC | A child with a compass | Both |
| The Slime | Teardrop, two dots, a smile | Toriyama's illustrations | Square Enix | A 16-pixel sprite | Compression; unchanged 40 years |
| Totoro | A contour with a wide mouth | The film, no cuts | Studio Ghibli | A plush toy | The fidelity studio's one kernel |
| Emoji | 12×12, 18 bytes | Unicode | The Unicode Consortium | 250-character emails | Compression on a fidelity base |
| Football | 17 laws | The Laws of the Game | IFAB | Sailors; a bundle of rags | Compression; the world's game |
| Cricket | — | Dozens of laws; equipment; days | The MCC | The colonial state | Fidelity; the Commonwealth's game |
| The container | A standard box | ISO 668 | ISO | Every crane on earth | Compression; rebuilt world trade |
| TCP/IP | Working code; Postel's principle | RFCs | IETF | Heterogeneous networks | Compression beat OSI's archive |
| The metric system | Base units, decimal grammar | A cylinder in a vault, then a formula | BIPM | Everyone | Both; archive became physics |
| Pizza | Dough, red, cheese, round | AVPN rules; UNESCO | AVPN | Every kitchen | Both; archive monetized by kernel's reach |
| Champagne | "Sparkling white" | The appellation | EU law | Every vineyard | Fidelity monetized; kernel uncontrolled |
| Newtonian physics | F = ma | *Principia* | Universities | Schoolrooms | Archive issued its kernel |
| Dragon Ball | Goku's silhouette; the Kamehameha | The Japanese magazine run | Shueisha, loosely | Foreign broadcasters; a podium | Compression; performed by heads of state |
| Studio Ghibli | Totoro (only) | Every film, no cuts | The studio | Cannes; a museum; a park | Fidelity; honored, not performed; kernel finally cut by an AI |
| Japanese soft power | Mario at Rio; the Kamehameha | Cultural Merit; prizes | The state, late | A global broadcast | State performs kernels, funds archives, cannot originate |

---

## 15. A Decision Guide

**If the goal is reach**, build the kernel first and build it for the narrowest channel the object will ever cross. Test it at sixteen pixels, in a glance, in a language you do not speak, after someone has re-cut it. If it survives, it will survive everything wider. Expect to lose control, credit for implementations, and revenue from reconstructions. Expect to gain the idiom.

**If the goal is accumulation**, build the archive and the institution to hold it, and accept that reach will be limited to those who can read the vocabulary. Issue a kernel from the archive before a stranger cuts one, and make sure it recovers the archive on inspection.

**If the goal is both**, which it almost always is, do what every surviving system has done: a kernel that anyone can carry and an archive that someone defends, with a documented relationship between them. The relationship is the product. The cross points at the creed; the creed points at the councils; a receiver can follow the chain inward as far as they wish, and most never will.

**If you are a latecomer** (a state, a corporation, an institution that did not make the thing), do not try to originate. Find the number that is already selecting kernels, ride what it has chosen, fund the archive if you can, and perform the kernel if you dare. The performance costs nothing and reaches further than the fund.

**If you are the author**, decide early whether you will be the kernel or the archive, because the two require incompatible temperaments. The compressor must tolerate mistreatment and anonymity; the archivist must tolerate obscurity and the role of institution. Toriyama and Miyazaki each chose, lived with it for forty years, and each was rescued, once, by a small dose of the other protocol he had not planned.

---

## 16. Limits and Counterexamples

A framework earns its keep by stating where it fails.

**The frontier moves.** When the channel widens faster than the object grows, both protocols can be pursued at once for a while. Hollywood in the studio era exported high-fidelity films to the whole world because celluloid and theaters were, for that object, a wide enough pipe; so did television in its monopoly decades. The tradeoff did not disappear; the scarce resource was elsewhere. It returned when the scarce resource became the viewer's attention, which is why the three-second vertical clip now governs what politicians do at podiums.

**Fidelity can spread by force.** Cricket is the counterexample to "compression always wins reach": the faithful game went wherever the British state went, which was a quarter of the planet. Latin, the Chinese script and the Vulgate all spread by empire. Empire is a channel-widener that the compression protocol does not need and the fidelity protocol often does, and it is expensive. When the empire withdraws, the archive stays where the empire put it and the kernel keeps moving.

**Some kernels are built by committees.** The Olympic rings were drawn by one man but adopted by a committee; the metric system was designed by a commission; Unicode is a consortium. The framework's claim is narrower than "committees cannot make kernels": it is that committees cannot *select* kernels for a public, because selection requires a number, and a committee's number is its own vote. The rings and the meter were selected by a century of use after the committee acted.

**Korea.** The Korean state is often credited with manufacturing the Korean wave after the 1997 financial crisis, and the Cool Japan Fund was explicitly modeled on it. The record is subtler: the state funded infrastructure, training and export promotion, while the kernels (the songs, the idols, the dramas) were selected by charts, auditions and television ratings, numbers the state did not control. Korea is a case of a latecomer riding a number well, not of a committee originating a kernel.

**The AI filter.** The 2025 Ghibli-style images are the hardest case because they are a kernel cut by a machine from an archive that refused to issue one, applied by receivers with no idiom in common, at a scale no human compression ever reached. Whether this is the compression protocol's final form or a new protocol altogether is not yet decidable from one case. What can be said is that it obeys Law 8: an archive that will not compress itself will be compressed by someone else, and the someone else will not ask.

---

## 17. Sources

**Theory**
- Shannon, Claude E., "A Mathematical Theory of Communication," *Bell System Technical Journal* 27 (1948)
- Shannon, Claude E., "Coding Theorems for a Discrete Source with a Fidelity Criterion," *IRE National Convention Record* (1959)
- Kolmogorov, Andrei N., "Three Approaches to the Quantitative Definition of Information," *Problems of Information Transmission* 1 (1965)
- Eigen, Manfred, "Selforganization of Matter and the Evolution of Biological Macromolecules," *Naturwissenschaften* 58 (1971)
- Dawkins, Richard, *The Selfish Gene* (Oxford, 1976), ch. 11
- Sperber, Dan, *Explaining Culture: A Naturalistic Approach* (Blackwell, 1996)
- Bartlett, Frederic C., *Remembering* (Cambridge, 1932)
- Boyd, Robert, and Peter J. Richerson, *Culture and the Evolutionary Process* (Chicago, 1985)
- Lord, Albert B., *The Singer of Tales* (Harvard, 1960)
- Ong, Walter J., *Orality and Literacy* (Methuen, 1982)
- Eisenstein, Elizabeth L., *The Printing Press as an Agent of Change* (Cambridge, 1979)
- Benjamin, Walter, "The Work of Art in the Age of Mechanical Reproduction" (1935)
- McCloud, Scott, *Understanding Comics* (1993)
- Cohn, Neil, and Sean Ehly, "The vocabulary of manga," *Journal of Pragmatics* 92 (2016)
- Nye, Joseph S., *Bound to Lead* (Basic Books, 1990); *Soft Power* (PublicAffairs, 2004)
- Christensen, Clayton M., *The Innovator's Dilemma* (Harvard Business School Press, 1997)
- Gabriel, Richard P., "Lisp: Good News, Bad News, How to Win Big" (1991), the "worse is better" essay
- Postel, Jon, RFC 760 and RFC 761 (1980), the robustness principle

**Cases**
- Wills, Garry, *Lincoln at Gettysburg* (Simon & Schuster, 1992)
- Darwin, Charles, *On the Origin of Species*, 1st ed. (1859) and 5th ed. (1869); Spencer, Herbert, *Principles of Biology* (1864)
- Pickthall, Marmaduke, *The Meaning of the Glorious Koran* (1930)
- Daniell, David, *William Tyndale: A Biography* (Yale, 1994)
- Levinson, Marc, *The Box: How the Shipping Container Made the World Smaller* (Princeton, 2006)
- Russell, Andrew L., *Open Standards and the Digital Age* (Cambridge, 2014), on OSI and TCP/IP
- Goldblatt, David, *The Ball Is Round: A Global History of Football* (Viking, 2006)
- Sterne, Jonathan, *MP3: The Meaning of a Format* (Duke, 2012)
- Helstosky, Carol, *Pizza: A Global History* (Reaktion, 2008)
- Issenberg, Sasha, *The Sushi Economy* (Gotham, 2007)
- UNESCO, "Art of Neapolitan 'Pizzaiuolo'," Representative List (2017)

**The Japanese experiment** (full sourcing in the companion essays)
- Kanzenshuu translations and timeline: https://www.kanzenshuu.com/
- Napier, Susan J., *Miyazakiworld: A Life in Art* (Yale, 2018)
- Denison, Rayna, *Studio Ghibli: An Industrial History* (Palgrave, 2023)
- Emojipedia, "Correcting the Record on the First Emoji Set" (Mar. 8, 2019): https://blog.emojipedia.org/correcting-the-record-on-the-first-emoji-set/
- Fast Company, "The Oral History of the Poop Emoji" (Nov. 18, 2014): https://www.fastcompany.com/3037803/the-oral-history-of-the-poop-emoji-or-how-google-brought-poop-to-america
- Anime News Network, "Heads of Japan, France Trade Dragon Ball's Kamehameha" (Apr. 2026): https://www.animenewsnetwork.com/cms/.236199
- Anime News Network, "Newspapers: Japanese Government to Abolish Cool Japan Fund" (Aug. 20, 2026): https://www.animenewsnetwork.com/news/2026-08-20/newspapers-japanese-government-to-abolish-cool-japan-fund/.240760
- Jiji Press, "Cool Japan Fund Faces Potential Abolition" (June 25, 2026): https://english.adnkronos.com/2026/06/25/cool-japan-fund-faces-potential-abolition/
- Holland, Oscar, "Viral Studio Ghibli-style AI images showcase power – and copyright concerns – of ChatGPT update," CNN (Mar. 28, 2025)
- Wikipedia: "Studio Ghibli," "Hayao Miyazaki," "Isao Takahata," "Akira Toriyama," "Slime (Dragon Quest)," "Emoji," "Warriors of the Wind"
