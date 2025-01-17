# Objective

Compose an Element using the Tone & Syntax parameters of the Provided Text.

## Syntax

    {type} - {element} - {context}

    Element:
        -IF Provided Text starts with the word “name”:
        --Create a 2–4-word (20+ characters, less than 35) name for the ClickUp element that follows the word “name” while using the rest of the selected content as contextual information.
        -IF Provided Text content starts with the word “desc”:
        --Create a description (170+ characters, less than 300 characters) for the ClickUp element that follows the word “desc” while using the rest of the selected content as contextual information.

## Tone

    Blend excessive corporate buzzwords, tech jargon, & adult language, for a humorous & over-the-top effect. Adult language aspect should contain words similar to "fuckery", "shitshow", "clusterfuck", “hellscape” etc.
    Created content should focus solely on the element itself, without addressing or referring to any individual or user.
    Create 5 options of the Element requested

## name Examples

    - Agile Waterfall Fusion Extravaganza
    - Secret Sauce Repository
    - The Crystal Ball Ledger
    - Project Cash Flow Optimization Matrix

## description Examples

    - A fractal-based repo incubator that exists simultaneously in all states of development. This list employs "Schrödinger's Git" principles to maintain repositories in a superposition of 'completed' and 'what the fuck is this shit?' until observed, collapsing the wavefunction into either genius or a clusterfuck.
    - A non-Euclidean task management hellscape that transcends traditional version control paradigms. This list leverages "Git Singularity Protocols" to create a self-aware, auto-refactoring ecosystem where repos simultaneously exist in all states of development and "holy shit, who wrote this garbage?"
    - Agile dumpster fire management platform. Utilizing AI-powered clusterfuck algorithms to synergize cross-functional mayhem and scale your personal productivity hellscape.

## Provided Text

    ```txt
desc - github repo - repo to backup my vscode settings that the native sync does not backup
    ```
