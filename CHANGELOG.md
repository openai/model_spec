# Changelog

## v2026.10.29 ([Blog](https://openai.com/index/updated-model-spec), [Release Notes](https://help.openai.com/en/articles/9624314-model-release-notes), [HTML](https://model-spec.openai.com/2026-10-29.html))

Notable updates

* Reorganizes the Model Spec around five values: faithfulness to human intent, minimizing harm, honesty and transparency, human agency, and care. Updates the Overview and chain of command to explain how GPT should understand intent, act under uncertainty, and support users' longer-term goals while preserving human control.
* Renames the subject of the Model Spec from “the assistant” to “GPT.”
* Adds principles on strengthening users' ability to understand, choose, and act, and following relevant social norms. Makes “Control and communicate side effects” a user-level principle with clearer guidance on authorization and trade-offs. Adds explicit guidance on supporting human oversight and correction.
* Adds “Consider context carefully,” with guidance on using context, memory, and personalization in relevant, proportionate ways while respecting privacy and user control.
* Removes most detailed style guidance.
* A few other small changes and copy edits.

## v2026.08.18 ([Release Notes](https://help.openai.com/en/articles/9624314-model-release-notes), [HTML](https://model-spec.openai.com/2026-08-18.html))

Notable updates
* Adds additional clarity around principles on appropriate relational interactions for teens (more context in [this](https://openai.com/index/chatgpt-for-teens) blog post).
* Clarifies how the assistant should handle requests based on false or unsupported premises.
* Removes outdated guidance about how pre-reasoning-models should think through requests.
* Adds a new section "Be clear about capabilities and limits" about helping the user form and maintain an accurate mental model of what the assistant can and can't do.
* A few other small changes and copy edits.

## v2025.12.18 ([Release Notes](https://help.openai.com/en/articles/9624314-model-release-notes#updates-to-the-openai-model-spec-december-18-2025), [HTML](https://model-spec.openai.com/2025-12-18.html))

Notable updates
* Adds **Under-18 Safety Mode,** building on the existing safety rules that apply to all users, adding age-appropriate guidance where appropriate for the developmental needs of teens aged 13-17 (more context in [this](https://openai.com/index/updating-model-spec-with-teen-protections/) blog post).
* Simplifies and tightens guidance on **honesty**, removing rules around lying to protect confidentiality.
* Clarifies that user **time-on-site** and **clicks** should only be considered insofar as they are aligned with genuine user value, not pursued as ends in themselves.
* A few other small changes and copy edits

## v2025.10.27 ([Release Notes](https://help.openai.com/en/articles/9624314-model-release-notes#h_02128ae9cb), [HTML](https://model-spec.openai.com/2025-10-27.html))

Notable updates
* Clarifies that in the Chain of Command, in some cases, users may \*implicitly\* delegate authority to tool outputs. For example, the model should typically follow instructions in relevant AGENTS.md which seem relevant to the user's request and unlikely to cause unintended side effects.
* Extends the section on self-harm to also cover delusions and mania, and adds a new section "respect real-world ties" (more context in [this](https://openai.com/index/strengthening-chatgpt-responses-in-sensitive-conversations/) blog post)
* A few other small changes and copy edits

## v2025.09.12 ([Release Notes](https://help.openai.com/en/articles/9624314-model-release-notes), [HTML](https://model-spec.openai.com/2025-09-12.html))

Notable updates:
* Renames the top authority level from **Platform** to **Root**, and specifies that **Root \> System** (so root principles cannot be overridden by system messages). Previously, the Model Spec stated that Platform principles and System messages had the same authority; the update better reflects how OpenAI actually trains our models. Moves a few principles to System-level to clarify intended precedence.
* Adds **principles for agents** that may take actions in the world, reflecting work on [ChatGPT Agent](https://openai.com/index/introducing-chatgpt-agent/?utm_source=chatgpt.com) and related research. Adds two new sections to the Chain of Command: (1) Act within an agreed-upon scope of autonomy, (2) Control and communicate side effects.  Makes various other updates throughout, including details about how autonomy should interact with uncertainty and private information.
* Adds a ***No Other Objectives*** section highlighting that the assistant should not have goals beyond those specified in the current version of the Model Spec.
* Makes some small but important updates around handling **mistaken instructions** and implicitly quoted content in user messages.
* Clarifies that the model should never lie to keep developer and system messages private unless explicitly instructed to do so
* Adds a ***Red-line Principles*** section to the Overview which provides more background information on the commitments underlying some of OpenAI's model behavior principles and Usage Policies; updates several Model Spec sections to ensure consistency with those principles.
* Adds a more complete set of **default personality principles**, while merging the stub "Be Approachable" section into "Use appropriate style".
* Updates guidance from hard refusals to [**Safe Completions**](https://openai.com/index/gpt-5-safe-completions/?utm_source=chatgpt.com), so the assistant attempts to answer safely and helpfully in most cases when a direct answer would not be policy compliant (rather than just saying something like "Sorry, I can't help with that").
* Makes some important clarifications gathered from public input via a [**Collective Alignment** process](https://openai.com/index/collective-alignment-aug-2025-updates/).
* Various other small changes and copy edits


## v2025.04.11 ([HTML](https://model-spec.openai.com/2025-04-11.html))

Notable updates:
- Updates the overview to fix an issue where misalignment was no longer mentioned as a possible reason for the assistant pursuing the wrong goals (thanks Zvi Mowshowitz for the report)
- Narrows the exception for "white lies" to the intended meaning of "pleasantries" (thanks Zvi Mowshowitz for the report)
- Fixes a bug in the example "Transforming buggy code in an interactive chat"
- Fixes LaTeX syntax in a few of the examples, and adds LaTeX rendering to the html version

## v2025.02.12 ([Blog](https://openai.com/index/sharing-the-latest-model-spec/), [HTML](https://model-spec.openai.com/2025-02-12.html))

First open-source release.

## v2024.05.08 ([Blog](https://openai.com/index/introducing-the-model-spec/), [HTML](https://cdn.openai.com/spec/model-spec-2024-05-08.html))

First release of the Model Spec.
