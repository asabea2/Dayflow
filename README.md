# dayflow

An AI-powered daily planner that generates a personalised to-do list 
based on your life context — built with vanilla JavaScript and the Claude API.

## what it does
- you fill in your energy level, what's going on in your life, 
  what must happen today, and what's hanging over you
- it calls the Anthropic Claude API and generates a structured daily plan
- tasks are organised by time of day, colour-coded by category, 
  and checkable as you go through your day

## how it works
Single-page HTML app. No backend, no database, no framework.
Browser → prompt construction → Anthropic API → JSON parsing → dynamic UI render.

## tech
- vanilla JavaScript (fetch API)
- Anthropic claude-sonnet-4-6
- structured JSON outputs
- DM Sans + DM Mono (Google Fonts)

## note
This is a personal tool. To use it you need an Anthropic API key 
added directly to the fetch headers in the source code.
