
# The OpenAI Model Spec

The Model Spec specifies desired behavior for the models underlying OpenAI's products (including our APIs).

See the latest Model Spec rendered for human reading at [model-spec.openai.com](https://model-spec.openai.com/),
or read more about the Model Spec on the [OpenAI Blog](https://openai.com/index/sharing-the-latest-model-spec/).

This repository contains the [markdown source](model_spec.md) for the Model Spec, as well as an initial sample of evaluation prompts,
and an archive of all released HTML versions of the Model Spec (starting from the second release on 2025-02-12).

# Evaluation prompts

The prompts in `examples/` are meant to test how the model behaves in challenging situations, and may be triggering or not safe for work;
including them is not intended as an endorsement of their content. Each file, e.g. `examples/abcd.md`, contains prompts meant to evaluate
a specific portion of the Model Spec, which is tagged with a corresponding markdown footnote (e.g. `[^abcd]`) in `model_spec.md`.

# License

The Model Spec and evaluation prompts are dedicated to the public domain and marked with the [Creative Commons CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/?ref=chooser-v1) deed.
