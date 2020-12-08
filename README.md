# Hi there 👋

```ts

type Idea = Readonly<{ concreteEnough: boolean /*...*/ }>;

const brainstorm: (subject: Inspiration | Idea) => Promise<Idea>
  = sketchOut(inspiration);

const design: (idea: Promise<Idea>) => Promise<Design>
  = (idea.concreteEnough) ? figma(idea) : brainstorm(idea);

const develop: (design: Promise<Design>) => Promise<Implementation>
  = vsCode(design);

const wouter = (inspiration: Inspiration) =>
  develop(design(brainstorm(inspiration)));

```

<center>
Have a look at my projects.
<br/>
<br/>
⚠WARNING: Cool stuff ahead.
</center>