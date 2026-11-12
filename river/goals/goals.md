package goals

# Goals

Why BirdView exists: what it enables for its readers, for the community whose data it uses, and
for the people who build it. Requirements cite goals in a `Goals:` field; a goal never lists its
requirements.

The first eight goals serve readers, the next two the community, and the next four the project.
The last two are root goals that the reader and community goals serve: the birders BirdView is
for, and the sources whose data it shows. Goals cite the goals they serve in `Serves:`.

## sizeIntuition

**Know how big a bird is**

See a bird's true size next to birds you already know.

Serves: [goals.detailMindedBirders](#detailmindedbirders)

## shapeNotOnlySize

**See how birds are built**

See how birds differ in proportion and build, not only in size.

Serves: [goals.detailMindedBirders](#detailmindedbirders)

## flexibleComparison

**Compare the birds you care about**

Compare any set of birds side by side, whether a family, a habitat, or a few you picked.

Serves: [goals.sizeIntuition](#sizeintuition), [goals.shapeNotOnlySize](#shapenotonlysize), [goals.detailMindedBirders](#detailmindedbirders)

## localRelevance

**Know what to expect where you are**

Learn which birds you could meet in a place and season, and how often each one is reported.

Serves: [goals.detailMindedBirders](#detailmindedbirders)

## honestData

**Trust what you see**

Know where each figure comes from, how certain it is, where sources disagree, and what is missing.

Serves: [goals.detailMindedBirders](#detailmindedbirders), [goals.sourcesShowcased](#sourcesshowcased), [goals.giveBack](#giveback)

## openToEveryone

**Usable by anyone, anywhere**

Read BirdView whatever your eyesight, device, or connection.

## shareableViews

**Share what you find**

Bookmark or send any view, and it keeps working.

## readerPrivacy

**Browse privately**

Use BirdView without being identified or tracked.

## goodDataCitizen

**Respect the sources**

Honor the terms of, and credit, every person and project whose data BirdView uses.

Serves: [goals.sourcesShowcased](#sourcesshowcased)

## giveBack

**Give back to the commons**

Make what BirdView derives open for others to check, reuse, and improve.

Serves: [goals.sourcesShowcased](#sourcesshowcased), [goals.honestData](#honestdata)

## rapidIteration

**Iterate quickly**

Build, run, and test BirdView on one machine, without refetching its data.

Serves: [goals.secure](#secure)

## freedomToChange

**Free to change**

Expose only what we mean to support, so everything else can change.

Serves: [goals.secure](#secure), [goals.rapidIteration](#rapiditeration)

## secure

**Stay secure**

Keep BirdView's attack surface small and its fixes quick to ship.

## maintainerPrivacy

**Protect maintainers' privacy**

Maintain BirdView without exposing anyone's personal details.

## detailMindedBirders

**Birders who love the details enjoy exploring birds' data**

Birders who enjoy the measurements, proportions, and records behind birds find BirdView worth
returning to and exploring.

## sourcesShowcased

**The people behind BirdView's data see it shown faithfully**

The researchers and projects whose data BirdView uses, such as AVONET and GBIF, find it a faithful,
well-credited viewer of their datasets.

## Non-goals

- **Bird identification.** BirdView assumes you know the bird.
- **Songs and calls.**
- **Range maps.** Regions filter the list; BirdView draws no maps.
- **Personal data.** No accounts, sightings, or life lists.
- **Commercial use.** BirdView is not and will not become commercial ([tech.localNowPublicLater](../requirements/local/tech/posture.md#localnowpubliclater)).
