## v0.0.1

**What's new?**

- Initial release.

## v0.0.2

**What's new?**

- Enhanced response generation
- Prompt optimizers added - *[code, shell_command]*
- Prompt optimizers added - *Console*
- Clear console  - *Console*

## v0.0.3

**What's new?**

- Busy bar index bug **fixed** - *(Console)*
- Other minor fixed.

## v0.0.4

**What's new?**

- Minor fixes 

## v0.0.5

**What's new?**

- Multiple variables renamed.
- First release under `python-tgpt`

## v0.0.6

**What's new?**

- `generate` is the default command. Thanks to @sameedzahoor
- Control response framing `--quiet`
- `generate` based prompt optimizaion - `--code` & `--shell`

## v0.0.7

**What's new?**

- Chat conversationally - *(Experimental)*
- Maintain chat history *.txt*
- Load chat history from file
- Chain request through *proxies*

## v0.0.8

**What's new?**

- Reading piped input as prompt - *(Console)*. Thanks to @sameedzahoor
- Reset conversation - *(Console)*
- View conversation history - *(Console)*
- Other minor fixes

## v0.0.9

**What's new?**

- Chatting conversationally - **Stable**

## v0.1.0

**What's new?**

- Chatting conversationally - **Default Mode**

## v0.1.1

**What's new?**

- Bug fixed - *file not found error*

## v0.1.2

**What's new?**

- Check version - `--version`
- Minor fixes.

## v0.1.3

**What's new?**

- Invalid response - **fixed**

## v0.1.4

**What's new?**

- Incomplete response - **fixed**

## v0.2.0

**What's new?**

- Multiple LLM providers

## v0.2.1

**What's new?**

- Fakeopen rendering issue fixed - [#7](https://github.com/Simatwa/python-tgpt/issues/7)

## v0.2.2

**What's new?**

- Package renamed to **pytgpt** - [#7](https://github.com/Simatwa/python-tgpt/issues/7)
- Visible vertical overflow - [#7](https://github.com/Simatwa/python-tgpt/issues/7)

## v0.2.3

**What's new?**

- Tabulated help info - `h`
- Control response vertical overflow behaviour.

## v0.2.4

**What's new?**

- [WebChatGPT](https://github.com/Simatwa/WebChatGPT/) added as provider
- Awesome-prompts manipulation commands = **CRUD**
- Other minor fixes.

## v0.2.5

**What's new?**

- New provider : [Bard](https://github.com/acheong08/bard) by **Google**.
- Check whole last response
- Other minor fixes.

## v0.2.6

**What's new?**

- Bug fixed - *reset conversation*  - **bard**
- Bug fixed - *low `httpx` logging level*. - **bard** 

## v0.2.7

**What's new?**

- Busy bar disabled when `--quiet` issued in *generate* mode. #12 Thanks to @johnd0e
- `interactive` takes action on `$ pytgpt` otherwise one has to explictly declare the action. #11

## v0.2.8

**What's new?**

- Auto-quiet on output redirection. Thanks to @johnd0e
- Dropped support for sourcing prompt from `stdin stream` in Windows. #12
- Colorized command prompt. <kbd>interactive</kbd>

## v0.2.9

**What's new?**

- Improved command prompt - *icon & color blending*
- Bug fixed - *multiline prompt in `interactive`*

## v0.3.0

**what's new?**

<details>

<summary>

- Improved introductory prompt

</summary>

*You're a Large Language Model for chatting with people.
Assume role of the LLM and give your response.*

</details>

- Combine both of piped and explicitly issued prompt #13
- Support piping input in Windows. #13
- Placeholder for piped input `{{stream}}` and copied text `{{copied}}`. 

## v0.3.1

**What's new?**

<details>

<summary>

41 New models. Thanks to [gpt4free](https://github.com/xtekky/gpt4free).

</summary>

 - AiChatOnline
 - Aura
 - Bard
 - Bing
 - ChatBase
 - ChatForAi
 - Chatgpt4Online
 - ChatgptAi
 - ChatgptDemo
 - ChatgptNext
 - Chatxyz
 - DeepInfra
 - FakeGpt
 - FreeChatgpt
 - GPTalk
 - GeekGpt
 - GeminiProChat
 - Gpt6
 - GptChatly
 - GptForLove
 - GptGo
 - GptTalkRu
 - Hashnode
 - HuggingChat
 - Koala
 - Liaobots
 - Llama2
 - MyShell
 - OnlineGpt
 - OpenaiChat
 - PerplexityAi
 - Phind
 - Pi
 - Poe
 - Raycast
 - TalkAi
 - Theb
 - ThebApi
 - You
 - Yqcloud

</details>

- **Aura** is the default provider
- Other minor fixes.

## v0.3.2

**What's new?**

- Added utility commands `utils` `gpt4free`  `update` etc
- Support g4f-based non-working providers. 
- Drop restriction to specific `g4f` dependency version (https://github.com/Simatwa/python-tgpt/issues/14#issuecomment-1899468911)
- Pass auth value to g4f-based providers. `-k`
- Support proxying in g4f providers

## v0.3.3

**What's new?**

- **gpt4free** gui interface - `web`
- `FakeGpt` - default provider.
- *Other minor updates.*

## v0.3.4

**What's new?**

- Auto-detect placeholders (#17)
- `Aura` - default provider

## v0.3.5

**What's new?**

- *Binaries for all system.*

## v0.3.6

**What's new?**

- New provider  - *Phind* . Resolves #18
- New util command `latest`. 
- `phind` is the default provider - *console*
- Fixed : `opengpt` - (#19)

## v0.3.7

**What's new?**

- *Binaries dependencies fixed.*

## v0.3.8

**What's new?**

- Phind fixed. #21
- Bard fixed. #23 #15
- Full and minimal executables.

## v0.3.9

**What's new?**

- Phind fixed. #https://github.com/Simatwa/python-tgpt/issues/21#issuecomment-1925326331

## v0.4.0

**What's new?**

- New provider - [Llama2](https://www.llama2.ai)
- New provider - [Blackboxai](https://www.blackbox.ai)
- Disable g4f version check.
- Partial or full installation options.

## v0.4.1

**What's new?**

- Rawdog : generate and execute python code in your system, driven by your prompts.

<details>

<summary>
For instance:

</summary>

   ```sh
   $ pytgpt generate -n -q "Visualize the disk usage using pie chart" --rawdog
   ```
   
   <p align="center">
   <img src="https://github.com/Simatwa/python-tgpt/blob/main/assets/Figure_1.png?raw=true" width='60%'>
   </p>
   
</details>


## v0.4.2

**What's new?**

1. RawDog:
   - Give consent to script execution
   - Execute script internally or externally
   - Choose python interpreter name

## v0.4.3

**What's new?**

- Minor bug fix. RawDog : *generate*

## v0.4.4

**What's new?**

- Execute python code in responses *(interactive)*- `exec`
- Execute python codes using system installed python interpreter - *default*
- Other minor fixes.

## v0.4.5

**What's new?**

- New model : **GPT4ALL** - Support offline LLM.

## v0.4.6

**What's new?**

- Revamped provider `webchatgpt`.
- Dynamic provider `g4fauto`. #29
- Test and save working g4f providers . #29
   ```sh
   pytgpt gpt4free test -y
   ```
- Order providers in ascending. #31

## v0.4.7

**What's new?**

- `g4fauto` fixed.

## v0.4.8

**What's new?**

- Execute scripts native interpreter - *rawdog*
- Typos fixed.
- Other minor fixes.

## v0.4.9

**What's new?**

- `webchatgpt` supports intro prompt.
- Fix: placeholders consistency - `{{stream}}|{{copied}}`
- Other minor fixes.

## v0.5.0

**What's new?**

- added: Provider [poe](https://poe.com). Supports multiple models. Thanks to [snowby666/poe-api-wrapper](https://github.com/snowby666/poe-api-wrapper).

## v0.5.1

**What's new?**

- added: Load variables from `.env` file.
- patch: Exclude selenium dependents providers from test. [#33](https://github.com/Simatwa/python-tgpt/issues/33)
- patch: Show more gpt4free models.
- added: Test logging flag.

## v0.5.2

**What's new?**

- fix: llama2. #34

## v0.5.3

**What's new?**

- added: Support for image generation.

## v0.5.4

**What's new?**

- fix: Gemini (Bard) provider.
- added: awesome prompts info.

## v0.5.5

**What's new?**

- patch: `FreeGpt` default g4f-based provider.
- added: `g4f` made required dependency.
- fix: `openai` response repetition. [#39](https://github.com/Simatwa/python-tgpt/issues/39)
- Other minor fixes.

## v0.5.6

**What's New?**

- added: Provider [Groq](https://console.groq.com/)


## v0.5.7

**What's New?**

- fix: Provider `Opengpt`.

## v0.5.8

**What's New?**

- added: Provider `perplexity`. Thanks to [HelpingAI/Helpingai_T2](https://github.com/HelpingAI/Helpingai_T2)

## v0.6.0

**What's new?**

- added : [FastAPI.](https://python-tgpt.onrender.com/docs)
- New extra - `api`

## v0.6.1

**What's new?**

- added : FastAPI - Image generation
- added : FastAPI - Providers endpoint.
- patch : FastAPI - existing endpoints

## v0.6.2

**What's new?**

- patch : FastAPI - `/images` amount > 10 causing http status_code 500.
- added : Hosted api health-status monitor.

## v0.6.3

**What's new?**

- added : API static contents - `clear` command.
   * `$ pytgpt api clear images`
- patch : Streaming redirected outputs. 
   * `pytgpt generate --raw "Write a short story" > shortstory.txt` #43
- other minor updates

## v0.6.4

**What's new?**

- feat : Dynamic provider - `auto` : *Working provider overally*.
- Other minor feats.

## v0.6.5

**What's new?**

- feat: New text provider - [YepChat](https://yep.com)
- feat: New image provider [Prodia](prodia.com)
- feat: Speech synthesise responses. `--talk-to-me` shortform  `-ttm`
- feat: Speech synthesise - **FastAPI** - `/audio`

## v0.6.6

**What's new?**

- feat: Minor mods
- addon: Telegram-bot - [pytgpt-bot](https://github.com/Simatwa/pytgpt-bot)

## v0.6.7

**What's new?**

- feat: Override chat intro.
- Other minor fixes.

## v0.6.8

**What's new?**

- fix: Failure to include intro in chat history - from `v0.6.6`

## v0.6.9

**What's new?**

- fix: Improper incomplete chat history generation.
- feat: Load intro from chat history file. *(first line)*
- feat: Set new `intro` on the fly. *(console)*
- feat: `en-US-Wavenet-C` - default voice for speech synthesis.
- fix: Perplexity AI raising `json.decoder.JSONDecodeError`

## v0.7.0

**What's new?**

> [!NOTE]
> This is a remarkable milestone. We have to do it in style.

- feat: **Asynchronous** implementation to all providers except a few.
- feat: **Asynchronus** implementation to all `FastAPI` endpoints.


## v0.7.1

**What's new?**

- fix: Failure to support g4f providers - `FastApi`
- feat: Rename `/audio` endpoints to `/voice` - `FastAPI`

## v0.7.2

**What's new?**

- feat: Extra installation requirement for Termux - `pip install python-tgpt[termux]`
- fix: Limit g4f requirement for binaries to **v0.2.6.1**

## v0.7.3

**What's new?**

- feat: Termux extra installation options : `termux-cli`, `termux-api` and `termux-all`

## v0.7.4

**What's new?**

- fix : Image generation failure.

## v0.7.5

**What's new?**

- feat: New provider - [Novita](https://novita.ai)

## v0.7.8

**What's new?**

- feat: Added prompt completions in interactive mode `cli`

## v0.7.9

**What's new?**

- fix: Remove providers: yepchat, opengpt, leo etc


## v0.8.1

**What's new?**

- feat: New provider **Ai4chat**