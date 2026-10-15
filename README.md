# paper-to-bullets

A Claude Code plugin with one skill: it turns a research paper into five bullets so you can decide in seconds whether to read it in full.

- **Title**: title, authors, year
- **Question**: what the paper asks
- **Method**: how it answers, in one line
- **Result**: the main finding, with the key number
- **Limitation**: stated, or marked "Implied:"

Missing items are written as "not stated" rather than guessed.

## Install

In Claude Code, add the marketplace and install the plugin:

```
/plugin marketplace add ori1992/paper-to-bullets
/plugin install paper-to-bullets@ori1992-skills
```

Then start a new session.

## Use

Ask Claude to skim, triage or summarise a paper, for example:

```
skim this paper for me: papers/example.txt
```

Or call the skill directly:

```
/paper-to-bullets papers/example.txt
```

## Layout

```
.claude-plugin/
  plugin.json        plugin name, version, description
  marketplace.json   marketplace "ori1992-skills", lists this plugin (source "./")
skills/
  paper-to-bullets/
    SKILL.md         the skill instructions
```
