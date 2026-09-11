# Quiz datasets

Quiz data belongs to the research layer because it is useful evidence for how a world model can be taught, tested, and operationalized.

## Layout

```text
quizzes/
└── worldmodel-dsl/
    ├── questions.json
    └── answers.json
```

The absorbed WorldModel DSL set contains 20 questions covering DSL format, entities, tooling, MCP, history, philosophy, and development environment.

Questions and answers remain separate so the corpus can be used both for testing and for generating new evaluation formats.
