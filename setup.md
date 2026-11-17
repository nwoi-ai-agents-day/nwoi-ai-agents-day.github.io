---
layout: page
title: Before you come
eyebrow: Setup
lead: Do these steps at home before the day. Then you can follow along on your laptop in the hands-on parts.
permalink: /setup/
---

## 1. Bring a laptop and charger

Bring the laptop you will work on, and its charger. In the hands-on blocks the
presenter does each step live on the screen. You can do the same on your
laptop if you want. The presenter comes round to help.

## 2. Install Claude Code or Codex and log in

You type the commands below in a terminal. A terminal is a window where you
type commands instead of clicking. On macOS, open the Terminal app. On
Windows, open PowerShell.

<div class="table-wrap" markdown="0">
<p class="cmd-caption"><strong>Claude Code</strong> <span class="muted">(Anthropic: Pro plan or higher)</span></p>
<table class="cmd-table" aria-label="Claude Code install steps">
  <tbody>
    <tr><th scope="row">macOS, Linux, WSL</th><td><code>curl -fsSL https://claude.ai/install.sh | bash</code></td></tr>
    <tr><th scope="row">Windows PowerShell</th><td><code>irm https://claude.ai/install.ps1 | iex</code></td></tr>
    <tr><th scope="row">Log in</th><td>new terminal: run <code>claude</code>, follow the browser prompt, then <code>/exit</code></td></tr>
    <tr><th scope="row">Test</th><td><code>claude --version</code> and <code>claude auth status --text</code></td></tr>
    <tr><th scope="row">Start safely</th><td><code>claude --permission-mode default</code> (Manual), in every new session</td></tr>
    <tr><th scope="row">Training off</th><td>once, in your Claude privacy settings (<a href="#data">step 4</a>)</td></tr>
  </tbody>
</table>
</div>
<!-- Claude Code: install commands, "open a new terminal window and run claude --version", free plan excludes Claude Code: https://code.claude.com/docs/en/setup ; log in by running `claude`: https://code.claude.com/docs/en/authentication ; `claude auth status --text`: https://code.claude.com/docs/en/cli-reference ; Manual mode: https://code.claude.com/docs/en/permission-modes -->

[Codex CLI](https://learn.chatgpt.com/docs/codex/cli) also works for this day.
Follow its install guide.
<!-- Codex CLI: "Inspect, edit, and run code from your terminal" (checked 3 Nov 2026): https://learn.chatgpt.com/docs/codex/cli -->

One agent is enough.

## 3. Your account

Bring your own account. You need an account that can run an agent to follow
along on your laptop. Without one, you can follow the demos on the screen.

## 4. Turn off model-improvement data use {#data}

Your provider may use what you type to improve its models. Turn this off
before you use the agent on your own work. This matters most for unpublished
data, personal data and data from partners.

<div class="cards cards-tight" markdown="0">
  <div class="card">
    <h3>Anthropic (Claude Code)</h3>
    <p>Free, Pro, Max: turn off model improvement in the privacy settings. Team, Enterprise and API: not used for training by default. Feedback you share has separate terms.</p>
  </div>
  <div class="card">
    <h3>OpenAI (ChatGPT, Codex)</h3>
    <p>Free, Plus, Pro: <em>on</em> by default. Turn off “Improve the model for everyone” (Data controls). It covers Codex tasks. Separately, turn off Codex's “Include environments” in Codex settings. The ChatGPT control does not change it. Business, Enterprise, Edu, API: off by default.</p>
  </div>
</div>
<!-- Anthropic: consumer choice, 5-year/30-day retention; settings at claude.ai/settings/data-privacy-controls; commercial and API not used for training: https://code.claude.com/docs/en/data-usage -->
<!-- OpenAI: "On personal workspaces with ChatGPT Free, Plus, or Pro, data sharing is enabled by default"; Improve the model for everyone or Do not train on my content: "Either option is sufficient for ChatGPT conversations and Codex tasks" (checked 3 Nov 2026): https://help.openai.com/en/articles/5722486-how-your-data-is-used-to-improve-model-performance ; "Codex has a separate Include environments setting ... Changing your ChatGPT setting ... does not change that setting": https://help.openai.com/en/articles/7730893-data-controls-in-chatgpt -->

<p class="muted">Checked on 27 October and 3 November 2026. Terms change.</p>

## 5. Setup help from 09:30

Walk-in and setup help start at 09:30, half an hour before the start. Come
early if your install does not work yet, or if you are not sure you are
logged in.

## No account?

You can still follow the demos. Every step in the hands-on blocks is shown
live on the screen.
