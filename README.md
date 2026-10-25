<p align="center">
  <img src="assets/logo.png" alt="HomeLLM" width="96">
</p>

<h1 align="center">HomeLLM</h1>

<p align="center"><b>Your own ChatGPT, at home.</b><br>A private AI assistant that runs on your PC and reaches your phone anywhere.<br>No account. No cloud. No one reading along.</p>

<p align="center">
  <a href="https://homellm.cloud"><img alt="homellm.cloud" src="https://img.shields.io/badge/homellm.cloud-coming%20soon-111111?style=flat-square"></a>
  <a href="LICENSE"><img alt="License: MIT" src="https://img.shields.io/badge/license-MIT-111111?style=flat-square"></a>
  <img alt="Runs offline" src="https://img.shields.io/badge/runs-offline-111111?style=flat-square">
  <img alt="Windows, Linux, macOS, phone" src="https://img.shields.io/badge/Windows%20%C2%B7%20Linux%20%C2%B7%20macOS%20%C2%B7%20phone-111111?style=flat-square">
</p>

<p align="center">
  <img src="assets/demo.gif" alt="Asking HomeLLM a question: the reply streams in on your own PC" width="900">
</p>

## What is HomeLLM?

HomeLLM gives you what the big AI apps give you, on hardware you own. Install it on a PC with a
graphics card, open it on any device in the house or anywhere else, and talk to a model that never
sends a word outside your home.

It is one download. On a capable PC it runs the model itself. On a phone, a laptop or in a browser it
is the same app, connected to the HomeLLM you already have.

<p align="center">
  <img src="assets/welcome.png" alt="HomeLLM start screen" width="900">
</p>

## What you get

**A real assistant.** Chat with memory across conversations, thinking modes you can tune and rename,
profiles with passcodes for everyone in the house, and an incognito mode that keeps nothing.

<p align="center"><img src="assets/chat.png" alt="A HomeLLM chat" width="900"></p>

**Writes code like the pros.** A side panel that writes files live, previews HTML and Markdown, edits in
place instead of rewriting, and lets you download the result.

<p align="center"><img src="assets/code.png" alt="The code panel next to a chat" width="900"></p>

**Edits you can watch.** When the assistant changes a file, the lines it replaces turn red and the new
ones appear in green as it types, and a GitHub-style diff lands under the reply. The code in the panel
is yours to edit too, with Ctrl+S, and every file has a live link that updates while you work.

<p align="center"><img src="assets/live-edit.gif" alt="The assistant editing a file: red lines out, green lines in, then the diff" width="900"></p>

**Your editor, your colours.** Six colour themes for the code panel, from GitHub Light to One Dark and Dracula.

<p align="center"><img src="assets/themes.png" alt="The code panel in the One Dark theme" width="900"></p>

**Uses a browser, with your consent.** A built-in browser the assistant can drive: open, read, click,
type. You choose how much it may do on its own, and every action shows as a card in the reply.

<p align="center"><img src="assets/browser.png" alt="The browser agent reading Wikipedia beside the chat" width="900"></p>

**Point at anything.** Pick an element on a page, see what it is, and add it to your message. The
assistant gets the selector, the role and the text, and finds the same element when it reads the page.

<p align="center"><img src="assets/picker.gif" alt="Picking an element on a web page and adding it to the chat" width="900"></p>

**Panels your way.** Dock the browser and the code panel left, right, top or bottom, fill the window,
resize with a grip, or run both side by side on a wide screen. Any of them opens in its own HomeLLM window.

<p align="center"><img src="assets/panels.png" alt="Code panel and browser side by side with the layout menu" width="900"></p>
<p align="center"><img src="assets/popout.png" alt="A file preview in its own HomeLLM window" width="640"></p>

**Reads the web for you.** A self-hosted search engine behind Web search and Deep research. Sources
show up as chips right in the text; hover one to see what it is, click to open it.

<p align="center"><img src="assets/sources.png" alt="Source chips in a reply with the hover card open" width="900"></p>

**Sees and hears.** Drop in photos and PDFs. Dictate with offline speech recognition, pick your
microphone, hold to talk.

**Finds the right model for you.** A setup wizard scans your graphics card and memory and recommends a
model that fits, with lighter and heavier options. Search any GGUF on Hugging Face, import your own, or
plug in a cloud AI key if you want one. Give models nicknames.

**Respects your PC.** The model sleeps when you are not using it and wakes on the next message. Gaming
mode hands the whole graphics card back to your games.

**Goes where you go.** Start a question on your phone, read the answer on your PC. Replies keep
streaming through a refresh or a lost connection.

<p align="center">
  <img src="assets/phone.png" alt="HomeLLM on a phone" width="300">
  &nbsp;&nbsp;&nbsp;
  <img src="assets/settings.png" alt="Browser agent consent settings" width="560">
</p>

## Two ways to run it

| | **HomeLLM** | **HomeLLM Server** |
|---|---|---|
| For | A PC with a graphics card, and every device that connects to it | A machine in a cupboard, a home server, a hosted box |
| Looks like | A desktop app with its own window, a phone app, a web page | No window. The engine and the API, managed from any HomeLLM app |
| Reach | This PC, the home network, or anywhere through the HomeLLM Network | Same, built for being reached from outside |
| Setup | Click the installer, run the wizard | One command, then pair your first device |

Devices pair once with a code. Nothing else can reach your HomeLLM, wherever it is.

## Status

**Code arrives soon.** HomeLLM is being built in the open and is already in daily use by its author.
The first public release includes the Windows desktop app, the server stack and the phone web app.

- [x] Chat, vision, dictation, web research, code panel
- [x] Setup wizard with hardware scan and model recommendations
- [x] Profiles, memory, incognito, power management
- [x] Browser agent with consent modes and an element picker
- [x] Live edits with diffs, editable code panel, colour themes
- [x] Dockable panels, side by side, pop-out windows
- [x] Cross-device replies, in-app updates
- [ ] HomeLLM Server package and installer
- [ ] HomeLLM Network: connect from anywhere with zero configuration
- [ ] Public release

Star the repository to be told when it lands, and watch [homellm.cloud](https://homellm.cloud).

## Why

The useful AI assistants all run on someone else's computer. Everything you type goes there, is stored
there and is read by whatever that company decides. A good open model on a normal gaming PC is now
enough for most of what people use ChatGPT for. HomeLLM is the missing piece: the polished app around
it, so running your own is not a weekend project.

## License

[MIT](LICENSE). Use it, change it, share it.
