# Shopify Theme Developer Challenge

## Overview

This take-home challenge is designed to evaluate how you work within an existing Shopify theme codebase.

You will be provided the following by email:

- A development store URL and password
- A Figma URL
- A `shopify.theme.toml` file or environment details to configure it
- A GitHub repository URL
- Any additional access or setup instructions

Please plan to spend **2-3 hours** on this exercise.

## Goal

Using the provided Figma reference, implement:

- One **Story Telling** section
- One **Product Collection** section

Both sections should be built for use in the Shopify theme editor and should feel native to the existing theme architecture.

## Setup

1. Clone the GitHub repository provided in the email.
2. Configure your local `shopify.theme.toml` using the provided development store details.
3. Start the theme locally using either of the following:

   ```sh
   npm run dev
   ```

   or

   ```sh
   shopify theme dev --environment main
   ```

## Requirements

- Build one Story Telling section based on the provided Figma design.
- Build one Product Collection section based on the provided Figma design.
- Make both sections configurable through the Shopify theme editor.
- Use the most reusable implementation you can within the existing theme structure.
- Prefer theme blocks over shared snippets and housed in theme sections.
- Include at least **one reusable piece of UI** shared between the two sections.
- Match the provided design as closely as practical while keeping the implementation maintainable.
- Ensure the implementation works responsively across relevant screen sizes.
- Do **not** use AI-generated code or external libraries for this exercise.

## Submission

Submit your work as a GitHub pull request.

In the PR description, include brief notes covering:

- Your implementation approach
- What you made reusable and why
- Any tradeoffs, assumptions, or incomplete pieces
- Any setup notes we should know when reviewing

## What We're Looking For

- Fidelity to the Figma design
- Clean, maintainable code
- Thoughtful reuse of sections, blocks, snippets, or shared UI patterns
- Good use of Shopify theme editor settings and configurability
- Responsive implementation quality
- Comfort working within an existing Shopify theme architecture
- Clear setup and developer workflow

## Constraints

- Use the provided codebase as the foundation for your work.
- Avoid adding third-party libraries.
- Avoid using AI tools to generate or complete the implementation.
- Keep the solution practical, readable, and consistent with the existing theme.
