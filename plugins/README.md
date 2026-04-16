This folder holds the functional parts of the system.

Each plugin has one job.

gcb-knowledge
This plugin injects GCB context into conversations.

It should be a Provider.

That means it quietly helps Enoch answer with the right theological context.

gcb-ontology
This plugin checks whether outputs match your required GCB structure.

It should be an Evaluator.

That means it checks output quality and consistency.

gcb-repo-router
This plugin helps users find the right repo, file, or link.

It should be an Action.

That means it only runs when somebody asks for a resource.

gcb-content
This plugin handles content generation for social or publishing workflows.

At first it should run in safe mode.

gcb-moderation
This plugin prevents hallucinations, unsafe theology, or bad output.

It should include a kill switch.

gcb-token
This plugin handles the future Web3 layer.

At first it should only read wallet or token data.
It should not move funds during early development.
