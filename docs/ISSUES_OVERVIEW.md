# Issues Overview

## 📊 Statistics

- **Total Issues**: 183
- **Open**: 116
- **Closed**: 67
- **Close Rate**: 36.6%
- **Last Updated**: 2025-10-11

## 📑 Table of Contents

- [Feature Requests](#feature-requests)
- [Bug Reports](#bug-reports)
- [Installation Issues](#installation-issues)
- [Configuration Issues](#configuration-issues)
- [Compatibility Issues](#compatibility-issues)
- [Documentation Improvements](#documentation-improvements)
- [Resolved Issues](#resolved-issues)

---

## 🚀 Feature Requests

### Open Issues

#### #215 chrome_console incomplete data retrieval
- **Status**: OPEN
- **Author**: africa1207
- **Date**: 2025-09-30
- **Description**: chrome_console returns shallow copy data, cannot get deep object information

#### #207 Screenshots can't autosave? I have to manually click Save?
- **Status**: OPEN
- **Author**: FVEFWFE
- **Date**: 2025-09-18
- **Description**: Request for automatic screenshot saving without manual clicking

#### #205 Support clipboard information retrieval for form filling
- **Status**: OPEN
- **Author**: sunzh231
- **Date**: 2025-09-17
- **Description**: Fill input fields directly from clipboard to avoid CSP blocking inject scripts

#### #202 How to use this plugin in Electron applications
- **Status**: OPEN
- **Author**: lyl340321
- **Date**: 2025-09-13
- **Description**: Want to reuse this plugin to provide MCP service in Electron browser

#### #201 chrome-mcp cannot retrieve information from dialog
- **Status**: OPEN
- **Author**: qphien
- **Date**: 2025-09-12
- **Description**: Dialog contains token sensitive information, js retrieval returns empty

#### #200 How to scroll the page
- **Status**: OPEN
- **Author**: qphien
- **Date**: 2025-09-12
- **Description**: On Mac, space key doesn't scroll Chrome page

#### #190 No support for offline local model loading?
- **Status**: OPEN
- **Author**: long36708
- **Date**: 2025-09-02
- **Description**: In internal network environment, cannot download HuggingFace models

#### #183 How to save large HTML content from Chrome browser
- **Status**: OPEN
- **Author**: sansanai
- **Date**: 2025-08-28
- **Description**: How to save HTML displayed in Chrome browser, especially when content is large

#### #180 Service status frequently stops unexpectedly
- **Status**: OPEN
- **Author**: IAmKongHai
- **Date**: 2025-08-28
- **Description**: Request to maintain service running until browser exits

#### #178 Browser automatically pops up when MCP opens pages
- **Status**: OPEN
- **Author**: MiloQ
- **Date**: 2025-08-27
- **Description**: Request for browser to run silently in background

#### #177 n8n integration
- **Status**: OPEN
- **Author**: judaemon
- **Date**: 2025-08-27
- **Description**: Can this be used in n8n workflow?

#### #175 Can MCP server start in SSE mode?
- **Status**: OPEN
- **Author**: FriSeaSky
- **Date**: 2025-08-25
- **Description**: Currently only supports two modes, hope to implement SSE mode

#### #171 Tab group api controls
- **Status**: OPEN
- **Author**: danieliser
- **Date**: 2025-08-21
- **Description**: Allow MCP to control tab groups: create, delete, add tabs to groups, etc.

#### #169 Feature Request: Support Environment Variables to Disable Specific Tools
- **Status**: OPEN
- **Author**: lathidadia
- **Date**: 2025-08-20
- **Description**: Support disabling or filtering specific tools via environment variables to resolve tool name conflicts

#### #162 Needs rate limit logic to prevent tools going rogue
- **Status**: OPEN
- **Author**: neberej
- **Date**: 2025-08-16
- **Description**: Need to add rate limiting logic to prevent tool abuse

#### #157 Chrome Web Store
- **Status**: OPEN
- **Author**: nelzomal
- **Date**: 2025-08-13
- **Description**: Any plans to publish to Chrome Web Store?

#### #155 More intelligent
- **Status**: OPEN
- **Author**: nullCode666
- **Date**: 2025-08-13
- **Description**: Hope MCP can automatically understand webpage source code, find encryption methods, etc.

#### #153 `chrome_inject_script` not working on some sites
- **Status**: OPEN
- **Author**: rmorse
- **Date**: 2025-08-12
- **Description**: chrome_inject_script doesn't work on some sites, need support for different injection points

#### #141 Support mouse hover and multi-window MCP isolation
- **Status**: OPEN
- **Author**: lironghai
- **Date**: 2025-08-07
- **Description**: Request mouse hover and multi-window MCP isolation features

### Closed Issues

#### #145 Add file upload capability for web forms
- **Status**: CLOSED
- **Author**: kaovilai
- **Date**: 2025-08-08
- **Description**: Add file upload functionality to support web forms

#### #107 Support .dxt format
- **Status**: CLOSED
- **Author**: metalshanked
- **Date**: 2025-07-16
- **Description**: Support Anthropic's .dxt format for one-click installation

---

## 🐛 Bug Reports

### Open Issues

#### #215 chrome_console incomplete data retrieval
- **Status**: OPEN
- **Author**: africa1207
- **Date**: 2025-09-30
- **Description**: chrome_console returns shallow copy, deep objects show as "object"

#### #212 Tool invocation error
- **Status**: OPEN
- **Author**: zhaooa
- **Date**: 2025-09-28
- **Description**: Tool is open but still shows invocation error

#### #209 MCP tool called but drawing has no response
- **Status**: OPEN
- **Author**: scwlkq
- **Date**: 2025-09-26

#### #206 Request error
- **Status**: OPEN
- **Author**: lghxuelang
- **Date**: 2025-09-18
- **Description**: Invalid or missing MCP session ID for SSE

#### #204 Frequently opens chrome-extension://hbdgbgagpkpjffpklnamcljpakneikee/true
- **Status**: OPEN
- **Author**: Wouldyouplace45
- **Date**: 2025-09-15
- **Description**: Browser shows "cannot access your file"

#### #191 chrome_console requires current page not to have dev tool open
- **Status**: OPEN
- **Author**: string1225
- **Date**: 2025-09-03
- **Description**: Chrome browser mechanism limitation

#### #184 trae shows some tool names exceed 60 character limit
- **Status**: OPEN
- **Author**: wangqi996
- **Date**: 2025-08-29

#### #163 chrome_screenshot always gives "exceeds maximum allowed tokens" error
- **Status**: OPEN
- **Author**: maddada
- **Date**: 2025-08-18
- **Description**: Screenshot response exceeds maximum allowed tokens (25000)

#### #152 Concurrency execution errors
- **Status**: OPEN
- **Author**: shatang123
- **Date**: 2025-08-12
- **Description**: TabId misalignment and unclosed tabs during concurrent crawling

#### #149 Script injection failure message keeps appearing
- **Status**: OPEN
- **Author**: manzhonglu
- **Date**: 2025-08-11

#### #144 Opens webpage then waits until timeout
- **Status**: OPEN
- **Author**: shopkeeper2020
- **Date**: 2025-08-08

#### #142 Cannot perform click actions on opened webpage
- **Status**: OPEN
- **Author**: bbhxwl
- **日期**: 2025-08-07
- **Description**: Using qweb3 4b, only answers questions without performing click actions

#### #139 Error: Request timed out after 30000ms
- **Status**: OPEN
- **Author**: sunhao28256
- **Date**: 2025-08-05

#### #136 `chrome_keyboard` is not working with Claude Code
- **Status**: OPEN
- **Author**: hanayashiki
- **Date**: 2025-08-03
- **Description**: Shows success but nothing is input into textarea

#### #128 Keeps retrying if webpage element not found
- **Status**: OPEN
- **Author**: GragonForce666
- **Date**: 2025-07-29

#### #122 Various timeouts and automatic stops
- **Status**: OPEN
- **Author**: fordiy
- **Date**: 2025-07-26
- **Description**: Already increased 30s timeout by 10x, still having timeout issues

#### #118 Cannot auto-click Cloudflare CAPTCHA
- **Status**: OPEN
- **Author**: windzhu0514
- **Date**: 2025-07-23

#### #114 Cannot scrape Douban and Jike
- **Status**: OPEN
- **Author**: imHw
- **Date**: 2025-07-20
- **Description**: AI reports encountering problems accessing these sites, possibly anti-scraping mechanisms

#### #112 chrome_network_debugger maxRequests too small
- **Status**: OPEN
- **Author**: kanekanefy
- **Date**: 2025-07-19
- **Description**: maxRequests limit stops capture after 100 requests

#### #111 Error when taking website screenshot with CherryStudio
- **Status**: OPEN
- **Author**: GehuaZhang
- **Date**: 2025-07-18
- **Description**: Cannot read properties of undefined (reading 'map')

#### #99 chrome_get_web_content tool incomplete page information
- **Status**: OPEN
- **Author**: Reviel
- **Date**: 2025-07-13
- **Description**: Missing Description section when retrieving PostGIS ticket page

#### #92 AI cannot close alert dialogs
- **Status**: OPEN
- **Author**: chgblog
- **Date**: 2025-07-11
- **Description**: When encountering alert/confirm dialogs, AI cannot continue, shows MCP timeout

#### #67 Windows function call timeout error
- **Status**: OPEN
- **Author**: zhiyu
- **Date**: 2025-07-01

### Closed Issues

#### #181 The extension stays disconnected
- **Status**: CLOSED
- **Author**: Arefinw
- **Date**: 2025-08-28

#### #140 Semantic engine initialization failed
- **Status**: CLOSED
- **Author**: Demi555
- **Date**: 2025-08-06

#### #116 Extension disconnects when clicking connection then losing focus
- **Status**: CLOSED
- **Author**: BeginnerDone
- **Date**: 2025-07-22

#### #73 API Error: 413: Prompt is too long
- **Status**: CLOSED
- **Author**: Lehtien
- **Date**: 2025-07-04

#### #60 Claude code Chrome MCP server startup outputs emoji in console.log
- **Status**: CLOSED
- **Author**: gabyic
- **Date**: 2025-06-28
- **Description**: Causes MCP protocol JSON parsing error

---

## 📦 Installation Issues

### Open Issues

#### #210 Can extension configuration address be modified in Chrome?
- **Status**: OPEN
- **Author**: shenmadouyaowen
- **Date**: 2025-09-27
- **Description**: Can 127.0.0.1 be changed to 0.0.0.0 for LAN access?

#### #198 Plugin connection issue in Google Chrome
- **Status**: OPEN
- **Author**: nice-nicegod
- **Date**: 2025-09-09
- **Description**: Shows "Connected, Service Not Started". If Node.js installation path was changed, this issue occurs

#### #187 Shows "Connected, Service Not Started" when opening connection
- **Status**: OPEN
- **Author**: wyx66624
- **Date**: 2025-08-31
- **Description**: Manually registered mcp-chrome-bridge, port 12306 has no process listening

#### #174 Browser in Docker + Chrome MCP: troubleshooting
- **Status**: OPEN
- **Author**: f3l1x
- **Date**: 2025-08-25
- **Description**: Pre-installing extension in Docker virtual browser shows "Connected, Service Not Started"

#### #170 Claude Code integration on WSL
- **Status**: OPEN
- **Author**: TimHuey
- **Date**: 2025-08-20
- **Description**: Claude Code in WSL cannot recognize mcp server

#### #159 WSL Support?
- **Status**: OPEN
- **Author**: D3OXY
- **Date**: 2025-08-14

#### #151 How to initialize semantic engine in intranet?
- **Status**: OPEN
- **Author**: kkk123dm
- **Date**: 2025-08-12
- **Description**: Intranet usage, semantic engine initialization failed, embedded model download failed

#### #148 Chrome plugin started successfully but command line shows failed
- **Status**: OPEN
- **Author**: joytianya
- **Date**: 2025-08-10

#### #147 Any plans to support Docker deployment?
- **Status**: OPEN
- **Author**: tgscan-dev
- **Date**: 2025-08-10

#### #143 How to deploy this MCP service on server?
- **Status**: OPEN
- **Author**: no-bystander
- **Date**: 2025-08-08

#### #138 Chrome extension installed, can configure port
- **Status**: OPEN
- **Author**: KylanJimmy
- **Date**: 2025-08-05
- **Description**: Can 0.0.0.0 be bound instead of only 127.0.0.1?

#### #137 Windows: Connected, Service Not Started
- **Status**: OPEN
- **Author**: steven111920
- **Date**: 2025-08-04
- **Description**: Clicking run_host.bat shows access denied

#### #127 Connected, Service Not Started
- **Status**: OPEN
- **Author**: Fanzaijun
- **Date**: 2025-07-29

#### #115 Connected, Service Not Started
- **Status**: OPEN
- **Author**: yanghao112
- **Date**: 2025-07-21
- **Description**: Checked everything, still doesn't work

#### #106 Startup successful but cannot configure
- **Status**: OPEN
- **Author**: crxxxxxxx
- **Date**: 2025-07-15

#### #90 Cannot start
- **Status**: OPEN
- **Author**: qiffang
- **Date**: 2025-07-11
- **Description**: Running run_hosts.sh always hangs

#### #88 Failed to install on Apple Silicon Mac
- **Status**: OPEN
- **Author**: DaniloHandsOn
- **Date**: 2025-07-10
- **Description**: chrome-mcp-bridge command not found

#### #85 Session termination 400 error keeps appearing
- **Status**: OPEN
- **Author**: hcoona
- **Date**: 2025-07-08

#### #78 docs/CONTRIBUTING.md build instructions missing packages/shared build
- **Status**: OPEN
- **Author**: adrianlzt
- **Date**: 2025-07-06
- **Description**: Documentation missing shared package build steps

#### #68 Execute mcp-chrome-bridge -v and report [ERR_REQUIRE_ESM]
- **Status**: OPEN
- **Author**: coisini6
- **Date**: 2025-07-02
- **Description**: Windows10 reports ERR_REQUIRE_ESM error

#### #65 Mac M4 browser plugin service not connected
- **Status**: OPEN
- **Author**: wzp-coding
- **Date**: 2025-06-30
- **Description**: Followed troubleshooting guide, executing index.js hangs with no response

#### #62 Cannot start
- **Status**: OPEN
- **Author**: Mocha-s
- **Date**: 2025-06-28
- **Description**: Don't know how to start

### Closed Issues

#### #196 SOLUTION - Native Messaging not working in Chromium
- **Status**: CLOSED (resolved by PR #195)
- **Author**: gebeer
- **Date**: 2025-09-07
- **Description**: mcp-chrome-bridge npm package only installs to Chrome directory, doesn't support Chromium

#### #161 Unexpected error: Running Status --> "Connected, Service Not Started"
- **Status**: CLOSED
- **Author**: TonnyWong1052
- **Date**: 2025-08-15

#### #154 Chrome failed to load extension
- **Status**: CLOSED
- **Author**: mmhzlrj
- **Date**: 2025-08-12
- **Description**: Missing 'manifest_version' key

#### #81 Chromium browser startup failure directory issue
- **Status**: CLOSED
- **Author**: lesszzen
- **Date**: 2025-07-07
- **Description**: Chromium config directory on Linux is .config/chromium

#### #69 Any plans to adapt Firefox browser?
- **Status**: CLOSED
- **Author**: Shuai-S
- **Date**: 2025-07-02

#### #64 Doesn't support Linux deployment?
- **Status**: CLOSED
- **Author**: caiji2019-cai
- **Date**: 2025-06-30

#### #22 Mac startup failure, Native service not successfully started
- **Status**: CLOSED
- **Author**: DengKaiRong
- **Date**: 2025-06-19

#### #16 Development mode startup, server not successfully started
- **Status**: CLOSED
- **Author**: WSCZou
- **Date**: 2025-06-18

---

## ⚙️ Configuration Issues

### Open Issues

#### #203 INSTALL IN CURSOR, LOADING TOOLS, BUT NOT SUCCESS
- **Status**: OPEN
- **Author**: chenhunhun
- **Date**: 2025-09-14
- **Description**: Tools failed to load after Cursor configuration

#### #199 Claude code cli cannot connect
- **Status**: OPEN
- **Author**: 666xjs
- **Date**: 2025-09-10
- **Description**: Server running successfully but cannot connect

#### #188 Cannot connect in windsurf
- **Status**: OPEN
- **Author**: NoComments
- **Date**: 2025-09-02
- **Description**: Error: TransformStream is not defined

#### #185 Kiro prompts "Enabled MCP Server chrome-mcp-server must specify a command"
- **Status**: OPEN
- **Author**: Chris-C1108
- **Date**: 2025-08-29
- **Description**: Don't know what command refers to, might Kiro not support streamable-http type

#### #182 Claude CLI fails to connect to running server on macOS
- **Status**: OPEN
- **Author**: dreamreels
- **Date**: 2025-08-28
- **Description**: Extension shows running normally, but claude CLI tool cannot connect

#### #173 Claude code doesn't support streamableHttp
- **Status**: OPEN
- **Author**: Baddts
- **Date**: 2025-08-24
- **Description**: Claude code won't load this MCP after configuring streamableHttp

#### #168 Failed to parse MCP servers from JSON
- **Status**: OPEN
- **Author**: joyhu
- **Date**: 2025-08-19

#### #167 Claude code mcp cannot connect
- **Status**: OPEN
- **Author**: TheBloodthirster
- **Date**: 2025-08-18
- **Description**: Native connection disconnected

#### #160 Error using multilingual-e5-base
- **Status**: OPEN
- **Author**: lcylcyll
- **Date**: 2025-08-15
- **Description**: Model requires 768D dimension but errors in Chrome

#### #150 Readme Image not found - Installation Step 3
- **Status**: OPEN
- **Author**: amritbanerjee
- **Date**: 2025-08-12
- **Description**: Image link in Readme step 3 returns 404

#### #135 Where is the callTool() function library?
- **Status**: OPEN
- **Author**: hechengdu
- **Date**: 2025-08-03

#### #134 Cursor cannot connect to Chrome MCP
- **Status**: OPEN
- **Author**: shengcruz
- **Date**: 2025-08-02
- **Description**: Shows "No connection to browser extension"

#### #132 trae loading failed
- **Status**: OPEN
- **Author**: mimicode
- **Date**: 2025-08-02
- **Description**: chrome_send_command_to_inject_script length exceeds 60 characters

#### #131 Claude desktop not recognized after configuration
- **Status**: OPEN
- **Author**: microxxx
- **Date**: 2025-08-01

#### #124 Says drawing is done but Excalidraw is always blank
- **Status**: OPEN
- **Author**: fordiy
- **Date**: 2025-07-27

#### #123 Frequently auto-stops during AI output
- **Status**: OPEN
- **Author**: fordiy
- **Date**: 2025-07-26
- **Description**: Cannot continue drawing on original excalidraw page

#### #121 Cannot invoke after CherryStudio upgrade to 1.5.3
- **Status**: OPEN
- **Author**: csfeng1
- **Date**: 2025-07-26

#### #109 CherryStudio cannot use MCP properly
- **Status**: OPEN
- **Author**: kksqwerc
- **Date**: 2025-07-17
- **Description**: Tools listed but cannot be accurately invoked during conversation

#### #103 Error 400 generally means incorrect client configuration
- **Status**: OPEN
- **Author**: ifastcc
- **Date**: 2025-07-15
- **Description**: Provides correct configuration for Claude code, Gemini cli, Cursor

#### #102 Cherry-Studio startup failed
- **Status**: OPEN
- **Author**: Bboossccoo
- **Date**: 2025-07-14

#### #100 Cursor calling excalidraw prompts Error calling tool
- **Status**: OPEN
- **Author**: DevilMay-Cry
- **Date**: 2025-07-14
- **Description**: Request timed out after 30000ms

#### #101 VSCode usage: Input URL, input credentials. Stuck at opening URL
- **Status**: OPEN
- **Author**: kkk123dm
- **Date**: 2025-07-14

### Closed Issues

#### #221 How to configure mcp-chrome in VSC?
- **Status**: CLOSED
- **Author**: valuex
- **Date**: 2025-10-04
- **Description**: Cannot start server after configuration

#### #193 Cursor shows loading tools after adding MCP
- **Status**: CLOSED
- **Author**: lixiaolong613
- **Date**: 2025-09-04

#### #192 Connection reset after deploying to remote server
- **Status**: CLOSED
- **Author**: wlxwlxwlx
- **Date**: 2025-09-04

#### #164 How to use predefined prompt templates in Claude desktop?
- **Status**: CLOSED
- **Author**: WeiyangZhang
- **Date**: 2025-08-18

#### #133 Issue setting up MCP in Claude Code
- **Status**: CLOSED
- **Author**: seldaneg
- **Date**: 2025-08-02

#### #113 Error invoking remote method 'mcp:restart-server'
- **Status**: CLOSED
- **Author**: Daiyuxin26
- **Date**: 2025-07-19

#### #57 DIFY MCP invocation failed
- **Status**: CLOSED
- **Author**: SpringMeta
- **Date**: 2025-06-27

#### #45 Cherry Studio MCP connection error
- **Status**: CLOSED
- **Author**: nooldey
- **Date**: 2025-06-25
- **Description**: Incorrect serverType, should use camelCase

#### #32 VSCode startup failed
- **Status**: CLOSED
- **Author**: linjinxing
- **Date**: 2025-06-23

#### #30 Cannot use
- **Status**: CLOSED
- **Author**: 2513483494
- **Date**: 2025-06-23
- **Description**: unexpected status code: 400

#### #19 Error after configuring in Cursor
- **Status**: CLOSED
- **Author**: Sumouren1
- **Date**: 2025-06-18

#### #18 Doesn't support cursor/cline?
- **Status**: CLOSED
- **Author**: Rainmen-xia
- **Date**: 2025-06-18

#### #13 Cherry Studio addition failed
- **Status**: CLOSED
- **Author**: LLmoskk
- **Date**: 2025-06-17

#### #8 chrome_navigate invocation error
- **Status**: CLOSED
- **Author**: fcyf
- **Date**: 2025-06-16

---

## 🔌 Compatibility Issues

### Open Issues

#### #172 Iframe page elements not found
- **Status**: OPEN
- **Author**: Actor12
- **Date**: 2025-08-22
- **Description**: Webpages using iframe, chrome_fill_or_selector always not found

#### #126 Auto-reply, auto-publish hope for more powerful features
- **Status**: OPEN
- **Author**: smartchainark
- **Date**: 2025-07-29
- **Description**: Cannot complete tasks normally on X platform and Xiaohongshu platform

#### #93 How to get dynamic data?
- **Status**: OPEN
- **Author**: carter115
- **Date**: 2025-07-11
- **Description**: Data that calls API only when scrolling page

#### #43 [No data output] Cursor+Edge test drawing one month browsing history
- **Status**: OPEN
- **Author**: 3377
- **Date**: 2025-06-24

#### #42 Can it work together with Automa to create workflows?
- **Status**: OPEN
- **Author**: 3377
- **Date**: 2025-06-24

#### #40 Semantic engine initialization failed
- **Status**: OPEN
- **Author**: HY-Hu
- **Date**: 2025-06-24

#### #39 Permission issue keeps appearing
- **Status**: OPEN
- **Author**: mozhuangshu
- **Date**: 2025-06-24

#### #33 Cannot find element
- **Status**: OPEN
- **Author**: 2513483494
- **Date**: 2025-06-23
- **Description**: Tencent Cloud console page elements cannot be found

---

## 📚 Documentation Improvements

### Open Issues

#### #197 Cannot execute in commands
- **Status**: OPEN
- **Author**: lujuny328-cmyk
- **Date**: 2025-09-08
- **Description**: Putting link bridge in commands cannot execute

#### #189 Request to join group
- **Status**: OPEN
- **Author**: wwenj
- **Date**: 2025-09-02
- **Description**: Group QR code in documentation expired

#### #117 No tool to click extension programs?
- **Status**: OPEN
- **Author**: sunweihunu
- **Date**: 2025-07-22
- **Description**: Hope to add tool to click Chrome extensions

#### #125 QR code expired
- **Status**: OPEN
- **Author**: NuoLanC
- **Date**: 2025-07-29

### Closed Issues

#### #95 Document organization with images not as good as Playwright
- **Status**: CLOSED
- **Author**: Xuzan9396
- **Date**: 2025-07-12

#### #94 Readme video link expired
- **Status**: CLOSED
- **Author**: vcan
- **Date**: 2025-07-11

#### #91 Group is full, please add me
- **Status**: CLOSED
- **Author**: huangxingzhao
- **Date**: 2025-07-11

#### #89 What is this tool?
- **Status**: CLOSED
- **Author**: Messilimeng
- **Date**: 2025-07-11
- **Description**: Using Cursor, any good interactive prompts?

#### #84 How to configure my own AI?
- **Status**: CLOSED
- **Author**: liaoyu-zju
- **Date**: 2025-07-08

#### #83 WeChat QR code in Chinese documentation expired
- **Status**: CLOSED
- **Author**: YunfanGoForIt
- **Date**: 2025-07-07

#### #79 English?
- **Status**: CLOSED
- **Author**: michabbb
- **Date**: 2025-07-06
- **Description**: README is in English but Chrome extension is entirely in Chinese

#### #75 How to reference files in prompt directory?
- **Status**: CLOSED
- **Author**: jovezhong
- **Date**: 2025-07-05

#### #52 README multimedia resources 404 issue
- **Status**: CLOSED
- **Author**: yunkst
- **Date**: 2025-06-26

#### #49 What is the model chat tool on the browser right side in the video?
- **Status**: CLOSED
- **Author**: MoeMoeFish
- **Date**: 2025-06-25

#### #48 Suggest creating a WeChat group
- **Status**: CLOSED
- **Author**: goreycn
- **Date**: 2025-06-25

#### #44 Cannot see the MCP configuration link button
- **Status**: CLOSED
- **Author**: jimleee
- **Date**: 2025-06-25

#### #35 Drawing function not invoked
- **Status**: CLOSED
- **Author**: guangzhou
- **Date**: 2025-06-23

#### #34 How to draw on the board?
- **Status**: CLOSED
- **Author**: guangzhou
- **Date**: 2025-06-23

#### #31 Can console log reading be added?
- **Status**: CLOSED
- **Author**: ZoidbergPi
- **Date**: 2025-06-23

#### #26 Usage tutorial
- **Status**: CLOSED
- **Author**: fanhaoj
- **Date**: 2025-06-22

#### #23 How to open the dialog?
- **Status**: CLOSED
- **Author**: kokwiw
- **Date**: 2025-06-20

#### #17 Comparing 2 JD products exceeds token limit
- **Status**: CLOSED
- **Author**: namejee
- **Date**: 2025-06-18

#### #15 Claude Desktop
- **Status**: CLOSED
- **Author**: GoldRush520
- **Date**: 2025-06-18
- **Description**: Claude Desktop cannot be used in China, any alternatives?

#### #11 Can drag and drop functionality be added?
- **Status**: CLOSED
- **Author**: tom63001
- **Date**: 2025-06-17

---

## ✅ Resolved Issues

### Community Communication

#### #213 Request WeChat group for mutual communication
- **Status**: OPEN
- **Author**: zhangchao0323
- **Date**: 2025-09-29

#### #211 Request to join group, want to contribute to project
- **Status**: OPEN
- **Author**: suoaiyisheng
- **Date**: 2025-09-27

### Usage Issues

#### #176 Claude code cannot draw
- **Status**: OPEN
- **Author**: woshihoujinxin
- **Date**: 2025-08-26
- **Description**: Opens excalidraw.com to draw but no smooth effect

#### #166 Drawing problem
- **Status**: OPEN
- **Author**: fyture
- **Date**: 2025-08-18
- **Description**: Model says completed but nothing on excalidraw

### Python Integration

#### #194 How to integrate in code without AI agent?
- **Status**: CLOSED
- **Author**: dreambe
- **Date**: 2025-09-05
- **Description**: For example Python, any demo code?

#### #82 Failed to call tools directly using Python code
- **Status**: CLOSED
- **Author**: YunfanGoForIt
- **Date**: 2025-07-07

#### #24 Can this plugin be called using Python code?
- **Status**: CLOSED
- **Author**: liulint
- **Date**: 2025-06-20

#### #21 Can LLMs without MCP functionality connect to this MCP server?
- **Status**: CLOSED
- **Author**: JessiePen
- **Date**: 2025-06-19

### Server Deployment

#### #74 Suggestion: Enable External Access to Local Server
- **Status**: OPEN
- **Author**: ErrorGz
- **Date**: 2025-07-05
- **Description**: Suggest modifying HOST to 0.0.0.0 to allow external access

#### #72 Tab chaining issue
- **Status**: CLOSED
- **Author**: fundoop
- **Date**: 2025-07-04
- **Description**: Can specific tab page operations and tab switching be added?

#### #71 Can this MCP server be separated from client?
- **Status**: CLOSED
- **Author**: xiaodiao216
- **Date**: 2025-07-03

#### #70 [Help Wanted] What is the MCP client in project homepage video?
- **Status**: CLOSED
- **Author**: tonyxu721
- **Date**: 2025-07-03

### Others

#### #97 What is the conversation tool in usage examples?
- **Status**: CLOSED
- **Author**: sbwg
- **Date**: 2025-07-12

#### #96 Where is the entrance?
- **Status**: CLOSED
- **Author**: DavidCalls
- **Date**: 2025-07-12

#### #80 Alternative way question
- **Status**: CLOSED
- **Author**: yiminhale
- **Date**: 2025-07-06
- **Description**: Can npm be used instead of pnpm?

#### #51 Navigate function cannot open address in tab
- **Status**: CLOSED
- **Author**: adoin
- **Date**: 2025-06-26

#### #25 [Feature Request] - Can I use it with my Cursor?
- **Status**: CLOSED
- **Author**: DaleXiao
- **Date**: 2025-06-21

#### #14 How to support VSCode or trae?
- **Status**: CLOSED
- **Author**: loki-zhou
- **Date**: 2025-06-17

#### #5 How to set up MCP in Augment?
- **Status**: CLOSED
- **Author**: gally16
- **Date**: 2025-06-15

---

## 📈 Issue Trend Analysis

### High-Frequency Issue Types
1. **Installation/Configuration Issues** (~40%): Mainly Native Messaging connection failures, service not started
2. **Compatibility Issues** (~25%): Integration problems with different clients (Cursor, Claude Code, Cherry Studio, etc.)
3. **Feature Requests** (~20%): File upload, mouse hover, multi-window isolation, etc.
4. **Bug Reports** (~15%): Tool invocation errors, timeouts, element finding failures, etc.

### Common Solutions
1. **Permission Issues**: Use `chmod -R 755` to grant dist directory permissions
2. **Node.js Path Issues**: Reinstall Node.js to default path
3. **Configuration Format Issues**: Different clients use different configuration formats (streamableHttp vs streamable-http)
4. **Port Access**: Default 127.0.0.1, change to 0.0.0.0 for external access

---

## 🔗 Related Resources

- [Troubleshooting Guide](TROUBLESHOOTING.md)
- [Contributing Guide](CONTRIBUTING.md)
- [Tools Documentation](TOOLS.md)
- [Windows Installation Guide](WINDOWS_INSTALL_zh.md)

---

**Last Updated**: 2025-10-11  
**Data Source**: GitHub Issues API
