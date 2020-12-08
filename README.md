# Hi there 👋

```ts
// About me

type Idea = Readonly<{
  concreteEnough: boolean;
  meetsExpectations: boolean;
}>;

const brainstorm: (subject: Inspiration | Promise<Idea>) => Promise<Idea>
  = sketchOut(subject);

const design: (idea: Promise<Idea>) => Promise<Design>
  = (idea.concreteEnough && idea.meetsExpectations)
    ? makeMockups(idea)
    : design(brainstorm(idea));

const develop: (design: Promise<Design>) => Promise<Implementation>
  = vsCode(design);

const wouter = (inspiration: Inspiration) =>
  develop(design(brainstorm(inspiration)));
```

<div align="center">
Have a look at my projects.
<br/>
<br/>
⚠WARNING: Cool stuff ahead.
</div>